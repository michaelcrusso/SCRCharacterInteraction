# SCRCharacterInteraction
 Character Interaction RPG

## Premise

This is intended to be a very small proof of concept for weapons and speech systems that could be scaled up into a larger scenario. The idea is to use speech trees for interaction with all NPC characters, and to feature a combat system that does not actually rely on fundamental SC mechanics (i.e. there will be no usage of typical weapons, armor, or health), but instead triggers. It is currently intended to have up to four players, although I may shrink this to three.

## Combat

Currently, the sketch is to feature a combat system that relies on a "targeting reticule" in order to attack enemies. Your hero will automatically lock on to enemies that are within range or line of sight, and the targeted/locked enemy will be the target of any attacks or spells. In order to switch targets, you must select a hotkeyed dropship (which doubles as an inventory menu) and "flick" it. Alternatively, I may also add a button onto the hero units. 

As soon as dropship movement is detected, it will cycle your current target to the nearest other enemy target. Currently, this uses simple unit swapping to a computer player of the same color to achieve this effect seamlessly, but in the future this could use a unit loop instead to avoid order interruption and not require the use of "storage" players, expanding the number and difficulty of CPU enemies, as each computer player would be color-coded and represent a distinct level of enemy challenge. Once you have a lock, you can fire an arrow at your enemy by pressing a hotkey, which will create a special unit at your hero and order it to move to the targeted location. I'm undecided yet if it will be a "dumb" arrow and only land at the targeted location, meaning that if an enemy moves laterally (unlikely) it will miss, or if it will track the targeted enemy and then roll a chance to hit. Currently, the latter is closer to how the system actually works.

Melee combat will function similarly, although you will of course be required to be in range to hit your target, and you won't have to worry about arrow management (as arrows can run out). However, being in the line of attack, you will be more exposed to taking damage (which currently obey normal Starcraft rules, but will be triggered in the future) and reliant on parry and block skills.

## Skills

Similarly to Oblivion, the basic principle here will be; the more you use a skill, the more you will increase points in it. There will be no skill purchases or point allocation. Every time you roll a skill, such as an attack swing, a block, haggle, fire an arrow, or cast a spell, you will roll a chance to hit that will dictate success or failure (and in some cases, like spells, the degree of success). 

## Interaction

I would like to develop simple dialogue trees for every possible NPC in the game (considering that a fair number of them will be tagged as "generic" and feature approximately the same text, albeit with some randomly allocated rumors, or something).