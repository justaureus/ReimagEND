# ReimagEND
## A Terra pack designed to reimagine the End with new biomes, features, and terrain to explore

#### Includes overworld-like Aether zones throughout the outer end. Can be disabled by uncommenting the End-Only Source and commenting the ReimagEnd Source in `biome-providers\presets\default.yml`

Part of this pack uses resources from Astrash's Aeropelago pack, found [here](https://github.com/Astrashh/Aeropelago).

As of Terra version 6.2, there is no easy way to set generators on the Fabric and Forge platform implementations other than the overworld.  
Due to this, the only platform that you can easily use this pack on is the Bukkit version.  Please keep this in mind before creating issues related to the Fabric or Forge platforms.

#### This pack is a WORK IN PROGRESS.  It is currently survival ready however it is not feature complete.  Expect frequent changes which may be incompatible (i.e, cause chunk borders) with older versions of the pack. 

#### ADDITIONAL NOTE: There are no loot tables for custom dungeons (Ancient Towers & Mob Spawner Dungeons) at the moment. Vanilla End City loot tables are not affected.

## INSTALLATION
Follow this [installation guide](https://terra.polydev.org/install/index.html) for your particular platform.

#### Bukkit.yml Quick Reference 
##### Affects just the Vanilla End Dimension
```
worlds:
  world_the_end:
    generator: Terra:REIMAGEND
```
##### More than One Config Pack for Multiple Worlds 
```
worlds:
  world:
    generator: Terra:OVERWORLD
  world_the_end:
    generator: Terra:REIMAGEND
```
