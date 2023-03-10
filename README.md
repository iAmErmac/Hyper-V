# Hyper-V mod for Doom

![Hyper-V mod for Doom VR](https://i.imgflip.com/79fd43.gif)

Let my friend ChatGPT introduce this little mod:

Hyper-V is a Doom mod that adds a range of high-speed movement options, including dash, double jumps, teleportation, and grappling hooks. Players can use these mechanics to traverse levels quickly and efficiently, while still having the ability to punch their way through hordes of monsters with speed and agility

To download the Hyper-V mod click the download button below:

[![Download Now](https://raster.shields.io/github/downloads/iAmErmac/Hyper-V/total)](https://github.com/iAmErmac/Hyper-V/releases/latest)

[<img src="https://cdn.ko-fi.com/cdn/kofi2.png?v=2" height="36" alt="Buy me a Cofee!">](https://ko-fi.com/ermac)

## Features
* Double Jumps
* Foward Dash Move and Double-Dashes
* Ledge Climbing (hold jump key at any ledge to climb up)
* Teleport Move (Hold teleport button to select a spot for portal)
* Grappling Hook and Meat Hook (Use grappling hook on monsters to pull them in, ie. use as Meat Hook)
* Positional Melee Attack (Swing your hands at monsters to perform melee attacks)
* Increase/decrease player Sprint, Jump and Damage stats as you need
* Optional Auto Heals
* Can be used in regular, VR or dual-wield VR builds of gzdoom/lzdoom/questzdoom

## API
* now features an api to disable Positional Melee from other mods. Simply add a cvar named vmm_melee_disable in your mod and set it "true" in you script to disable Positional Melee from this mod

## Known Issues
* Player may get stuck at some places when using the Grappling Hook. Wait for 5 sec to be released
* Teleporting outside boundaries is possible and player may not be able to teleport back into the play area sometimes. In those cases use the Grappling Hook to try to return back or restart the level
* In restricted mode Teleport does not work on slopes and stairs. In unrestricted Teleport mode player may often land inside walls or ourside play areas
* Melee combo stun shake does not work in QuestZDoom by default. To enable screen shake increase earthquake shake intensity from Dislay Options

## Installation

Since it's an universal mod it can be used with any other mods and does not require any special load order. Although recommended to load after all the other mods to avoid any conflict

### GZDoom VR (PC-VR)

Latest GZDoom VR: https://github.com/hh79/gz3doom/releases/latest

Latest GZDoom VR Dual Wield version: https://github.com/iAmErmac/gzdoomvr/releases/latest

To install:

    Extract GZDoom-VR to a folder.
    Copy original doom wads into the folder.
    Copy this mod into the folder.
    Run with gzdoomvr.exe -iwad doom2.wad -file LATEST_HYPER-V_MOD
  
OR use DoomRunner: https://github.com/Youda008/DoomRunner/releases/latest to load mods with GZDoom

### QuestZDoom (Oculus Quest)

Official QuestZDoom: https://github.com/DrBeef/QuestZDoom/releases/latest

Unofficial QuestZDoom: https://github.com/emawind84/QuestZDoom/releases/latest

QuestZDoom launcher: https://github.com/baggyg/QuestZDoomLauncher/releases/latest

To install:

    Copy this mod into /sdcard/QuestZDoom/mods/
    Load QuestZDoom Launcher. select this mod along with others mods

## Recommended mods to combine with:

* [Universal Doom Weapons for VR:](https://github.com/iAmErmac/Universal_Doom_3DWeapons_VR)
  - This mod lets you use Doom Weapons (3d) with almost any mod

* [Universal Doom Voxel Weapons for VR:](https://github.com/iAmErmac/Universal_Doom_VoxelWeapons_VR)
  - This mod lets you use Doom Weapons (Voxel) with almost any mod
  
* [DamNums:](https://forum.zdoom.org/viewtopic.php?t=55048)
  - DamNums is a pretty simple concept: shoot monsters and little numbers pop out that tell you how much damage you did
  
* [Top HP Bars:](https://forum.zdoom.org/viewtopic.php?t=55048)
  - Really simple mod to add HP bars on top of enemies and players. Performance version is recommended for VR
  
* [Bolognese Universal Gore:](https://www.moddb.com/mods/brutal-doom/downloads/bolognese-gore-mod-v20)
  - A mod-friendly universal gore mod for Doom, Doom 2, Final Doom, Heretic, Hexen, Strife, Hacx, FreeDoom, Chex Quest and anything else you can run on Zandronum/GZDoom
  
* [Nash Gore:](https://forum.zdoom.org/viewtopic.php?t=62641)
  - The father of gore mods. The original brutal modification for (G)ZDoom returns, with a Vengeance

## Credits

* CVar loader zscript written by Alexander Kromm (m8f/mmaulwurff)
* Player Damage/Speed/Jump modifier and auto-heal zscript from Custom Doom and Ultimate Custom Doom mods
* Dash move zscript written by Apeirogon
* Ledge grab zscript written by dodopod
* Grappling/Meat-Hook zscript written by Agent_Ash aka Jekyll Grim Payne
* Double Jump, Teleport move and VR melee zscripts written by Ermac
* All the scripts combined and modified by Ermac

## 3D Model credits

* Grapple 3D Model - https://sketchfab.com/3d-models/grapple-f8a9ed3ff2f44fe18bc62d431255f71a
* All 3D models and model textures edited and modified by Ermac
