TableBreaker v1.1 - install: put this folder in the game's mods folder and add "TableBreaker" to modlist.txt.

Effect types the game really supports (read from game.unx):
mult_all, mult_self, mult_matching, add_value, add_value_all, add_value_per_die, double_score,
destroy_self, reroll_others, mult_all_destroy, give_card, give_die, roll_extra,
mult_if_highest, mult_if_odd, mult_if_even

INCLUDED
- Sextillion Die: add_value_all, 1e23 (100 sextillion). Closest match; exact behavior untested.
- Sum Die: add_value_per_die is only an APPROXIMATION of "extra value = total value of all dice".

NOT POSSIBLE with these types (removed): Squared Die (multipliers x themselves), Auto-Charge Ring.
Their sprites are still in sprites/ in case the game gets those effect types.

CHOOSING 10 RINGS / 10 DICE: the game has a built-in console with
  give dice <dice ID> <enchant ID> <quantity>   |   give ring <ring ID>   |   give card <card ID>
plus giveall (one of every die), goto, help. The ring limit and "already have this ring" checks still apply.
