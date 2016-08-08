# Morgue mod Prototype
## History
All graphical assets and original ideas/code are from [[A11 Terra Firma Mod Pack](https://ludeon.com/forums/index.php?topic=12580.msg126663#msg126663)] by **Saularian**
## Description
Add the possibility to bag bodies.
Bags can be crafted at both tailoring benches for 20 unit of any cloth types.
Filling bag with bodies is a quick task and take place at a new building : the morgue slab.![Morgue Slab](../Textures/Things/Buildings/Production/MorgueSlab.png)

A bagged body doesn't trigger bad mood (maybe they should still but less strong debuff then). A bagged body still need to be refrigerated (they rot in 4 days).
_Worth to note :_ Bagging a corpse **automatically strip it** (all you have to do is unforbid corpses and be sure to have a bill set at the slab - just like at the butcher table or crematorium).
## Bagged bodies can also be uses in several ways :
- harvest natural parts : turn 10 filled Bodybags into ~~several~~ natural parts (with medecine skills - **need to be balanced** - Maybe need 10 Bagged bodies for 1 or implanted harvested organs that will deterior (_HediffComp_Disappears_) / Give cancer / etc  ...) :
  - 2 Lungs / 2 Eyes / 1 Stomach / 1 Heart / 2 Kidneys / (1 Liver) / 1 Brain / 2 Ears / 1 Nose / 1 Jaw / 2 Arms / 2 Hands / 2 Legs / 2 Foots
- harvest artificial parts :
  - If possible, recovered parts should have increased infections chances or they can function at 50% efficiency for a little amount of time (how the hell should i code that!)
  - I was for 33% chance of destroying it, minimum
  - Maybe make "salvaged bionics" that need recipe "salvage bionics" + components = functional bionics (that way more different skills will be needed - adding to difficulty)
- turned into classic combustible
- run a corpses fueled generator :
  - Bodies in bag ~~should be~~ **are** able to be use by [CuproPanda's Corpse Generator](https://github.com/cuproPanda/CFG)
  - (add gaz powered one?)
- Crematation/~~normal burrying~~ (i would like to implement a early/tribal crematorium)
  - Apparently nearly impossible to burry modded items in grave (Corpses have special defs generated dynamically - in DLLs not in the XML files)
  - Add early wood fueled way of cremate bodies
    - Only for cremation and i would like it generate bad mood if cook has been prepared in this ceremonial/sacred building

## Also add :
(Maybe I should release them alone)
- Series of multi-purpose racked storage in several shapes. They also should support roof as a wall (for your very big storage urges).![Large rack storage](../Textures/Things/Buildings/Furniture/StorageLarge.png)
- A neon lamp

## Wild unorganised notes
- Maybe add a way to reclaim dirty/used bags and clean/rehabilitate them
- Bagged bodies should be able to be used in hoppers in order to be automatically used in different to-be-define contraptions
- Storages should be in two categories, refrigerated and not-refrigerated
