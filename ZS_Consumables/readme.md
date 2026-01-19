# Consumables

## Introduction

This provides a variety of consumable items for use in the game, enhancing gameplay and offering new strategies for players. Many are taken or inspired by other games and media such as BG3, NWN, and The Witcher. The mod distributes the items among vanilla stores as well as manually placed on some NPCs and automatically in the loot of some enemies randomly.

## New consumables types

All consumables are distributed and priced in a way that tries to serve as balance for their power. Use the configuration file to override any prices you want, as well as distribution, if it applies.

- **Elixirs**: powerful potions that provide powerful and long-lasting effects, but only one of them can be active at the same time. None of them stack with themselves either, a second consumption of the same elixir will refresh the duration.
  - Elixir of **Viciousness**: for 8 hours, benefit from a 5% critical hit chance, and whenever a creature is killed by the user, they gain a +2 damage and THAC0 bonus for 2 rounds (doesn't stack)
  - Elixir of **Bloodlust**: for 8 hours, hitting and killing enemies will heal the user in various amounts. Killing restores more health. Kills increase attacks per round by 1 for 2 rounds (doesn't stack)
  - Elixir of **Seeing the Invisible**: allows the user to see invisible creatures as per the detect invisibility spell. This effect triggers twice per round for 3 rounds, effectively giving them 6 opportunities to spot and dispel invisible creatures that aren't protected by Nondetection.
  - Elixir of **Universal Resistance**: for 8 hours, resist 25% of all elemental, poison, and magical damage, as well as 7% physical damage resistance. The user also is granted +2 bonus to Armor Class and saving throws.
  - Elixir of **Mystic Cultivation**: For 24 hours, spell casters gain +1 to all spell slots, and cast spells with a +1 bonus to casting speed, and +2 bonus to casting level, and deal 10% more elemental and magical damage. Does not stack. Only spellcasters can drink it.
- **Potion**: regular potion like vanilla ones. No restrictions.
  - Potion of **Minor Levitation**: allows the user to slightly hover above the ground, which grants immunity to most ground-based effects like web and grease. It also grants immunity to Slow and 35% faster movement speed for 3 turns. The effects do not stack with themselves, a second consumption of the same type potion will refresh the duration.
- **Oil**: a new category of consumables that provide various effects when applied to weapons for 8 rounds. This is taken straight from my old ZS_WeaponOils (now deprecated). Poisonous oils can cause self-poisoning, except blackguards and assassins are always immune. Others need to have at least 16 dexterity to avoid it, but thieves have a 50% chance of avoiding the damage either way; bards have a 30% chance. Only one oil may be active at a time, and a second application of the same oil will refresh the duration.
  - **Arcane** oil: deal 1d4+2 magic damage per hit for 8 rounds. Does not allow saving throw but is stopped by magic resistance.
  - **Caustic** oil: deal 1d2+1 acid damage per hit. Save vs. Breath for half, bypasses magic resistance.
  - **Gelid** oil: deal 1d2+1 cold damage per hit. Save vs. Breath for half, bypasses magic resistance.
  - **Scintillating** oil: deal 1d2+1 electric damage per hit. Save vs. Breath for half, bypasses magic resistance.
  - **Igneous** oil: deal 1d2+1 fire damage per hit. Save vs. Breath for half, bypasses magic resistance.
  - **Noxious** Oil: deal 1d2+1 poison damage per hit. Save vs. Poison to avoid poisoning: 6 poison damage over 2 rounds.
  - Drow **Soporific** Oil: save vs. Death and fall into a deep slumber for 1 turn. Damage wakes them up.
  - **Kuo-Toan** Oil of **Stunning**: Save vs. Spell at +2 or become stunned for 1 round. Considered a poison.
  - **Dragon Bile** Extract: non-dragons take 1 poison damage, and have their movement speed and strength reduced to half for 5 rounds if save vs. Death is failed.
  - **Dragonsbane** oil: a very expensive oil which causes 1d6+2 poison damage to dragons on hit (half to others) which severely weakens dragons for 3 rounds. This weakness can only apply once per 3 rounds, and fades progressively round by round. The pain it causes also has a 50% chance of disrupting their improved invisibility or stoneskin.
  - **Sanctified** oil: undead take +4 radiant damage per hit (effectively irresistible) each hit and they must save vs. Death at +2 or become slowed and weakened for 3 rounds (-3 Strength, -2 Armor Class)
  - **Profane** oil: identical to sanctified but only affects the living.
- **Remedy**: powerful concoctions that treat, cure, protect against, or dispel ailments.
  - **Angelic Reprieve**: powerful remedy that puts the character to sleep briefly. After the sleep, if it completed without interruptions, the character is healed and recovers a number of spell slots.
  - **Angelic Slumber**: a more powerful version that applies the equivalent to a full night of rest to the character after 1 turn of sleeping
  - **Basilisk** **Oil**: this compound reverts petrification and protects against petrification for 2 hours.
  - **Remedial Solution**: Cures the imbiber of all poisons, diseases, including blindness and silence. It also restores 12 HP and grants a slow regeneration that restores another 12 HP after 2 turns. This regeneration does not stack with itself, a second application of the same remedy will refresh the duration.
- **Throwables**: items that can be thrown at enemies to cause various effects (similar to Potion of Fire Breath or Explosions). None of these are treated as magical for the purposes of magical resistance.
  - **Acid vials**: throwable containers that deal minor acid damage instantly and once again after one round
  - **Alchemist fire**: throwable containers that deal fire damage in a small area and ignite targets.
  - **Choking powder**: throwable container that creates effectively a Stinking Cloud as per the wizard spell
  - **Tanglefoot bags**: throwable containers that create difficult terrain and ensnare targets as per the Entangle spell
  - **Web grenade**: throwable containing a web sack that explodes on contact with the ground, creating a webbed area as per the Web wizard spell.
  - **Grease** bottle: this bottle contains a thick, slippery grease that can be thrown on the ground to create a hazardous area. Any creature that moves through this area suffers the effects of the Grease spell.
  - **Pixie Dust**: you can throw a bunch of pixie dust into the air, making all targets in a small area invisible for 1 turn
  - **Holy Water**: throwable container that deals 3d4 magic damage plus 1d4 radiant damage to undead and fiends on a hit. Radiant damage cannot be resisted. They may be weakened if they fail a save vs. Death at +2, taking 15% more physical damage on hit for a few rounds. Magic resistance also doesn't affect it, and the negative effects do not stack on a second application, only their duration is refreshed.

When assessing durations, bear in mind that when an item says "hours", it means in-game hours, which in real-time are 5 minutes each. So an elixir that lasts for 4 hours lasts for 20 real-time minutes. This is how it works in vanilla as well. Only seconds, rounds, and turns refer to real-time.

## Compatibility

Should be compatible with everything as far as I know. Please offer feedback on balance and the supply of oils throughout the game if you try this. One caveat to mention is that it might be philosophically incompatible with other mods. For example, it might add bonuses that add up to too much if you have mods that give you insane bonuses already; or you might have a mod that also introduces "oils" or some such items, which would interfere in the sense that it would stack with my oils, when they shouldn't, as far as my design decisions.

Recommendations for install order:

- After any mods add content quest and new joinable NPCs
- After IWDification, if you install the spells, or SCS/ToF, if you use that source for the spells (but you shouldn't use that one)
- Before tweak mods, including my own ZSTweaks mod, if you use it

## Known issues

The noxious oil sometimes seems to not offer log feedback indicating whether the poisoning was resisted or not. I don't think it affects functionality though.

Additionally, applying the oils through the inventory will be through a button that states "drink potion", which doesn't make sense (trust me, don't drink them for real, you'll die), but I don't think that can be helped.

## Feedback & Future plans

If you have any ideas as to what things to add as a consumable, let me know! If I like it, I might add it, as long as it seems appropriate for the setting.

Let me know also of any bugs, and any other mods that might require compatibility with, and I'll see what I can do.

## Acknowledgements and credits

- Everyone on Discord for general help. They're a staple in my development process.
- CamDawg for his sensei knowledge
- zenblack for literally making every icon in this mod
