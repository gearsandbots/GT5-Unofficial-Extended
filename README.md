GT5-Unofficial-Extended
===

## About

GT5-Unofficial-Extended is a fork of Gregtech 5 Unoficial 5.09.52.582 aimed to fix outdated Bartworks code (including porting Bartworks UIs to modular ui 2), and rework stone age progression.
If this project is archived when you are reading this, it is beacuse this version's features have been merged into GT5-Unofficial, or I somehow have abandoned the project.

The original description is as follows:

GT5-Unnoficial is a decompiled and modified version of GT5.07.07. The goal of the mod is to maintain and extend the end
game of GT5. This version has been heavily modified for use with the GTNH modpack.

## Downloads

Builds of GT5-Unoficcial can be found on the [GTNH Jenkins Server](http://jenkins.usrv.eu:8080/job/Gregtech-5-Unofficial/).
If this link is dead, that means that something has happened to the host. 

## Installation

GT5U requires IndustrialCraft2-experimental. Version 2:2.2.828-experimental is recommended. 
Note: This is only if you are implementing it into a modpack. Importing into InteleJ IDEA will should automatically download the dependincies for mod development.

Forge versions 1428-1480 are known to break multiplayer. 1614 is recommended.

Place the downloaded jar file into your mods/ folder. A number of other mods may be required, see dependencies.gradle

## Issues

Please report any issues you to find to the main GTNH issue tracker. Include as much information as possible including
as version and steps to reproduce.

If you are having specific bugs related to this fork that go unresolved, please use the Github Bug report tool.

## Contribution

Please contribute to this or the original project! However, please take a note of
[current issues](https://github.com/GTNewHorizons/GT-New-Horizons-Modpack/issues), [Issues with this fork](https://github.com/gearsandbots/GT5-Unofficial-Extended/issues) and what is currently being worked on.

You don't need to clone the repository with full history to contribute, to save disk space and bandwidth you can clone:
```bash
git clone --depth 3 https://github.com/gearsandbots/GT5-Unofficial-Extended.git GT5-Unofficial-Extended
```
This way you'll get the last 3 commits of history in your local checkout, instead of all of it.

It is suggested to run `./gradlew build` inside your cloned repository before importing it to your IDE. This will reduce
the chance of strange errors.

## Attribution

Some textures/ideas have been taken from future versions of GT and texture pack authors for GTNH. Credit goes to Jimbno for the UU-Tex texture pack and its contributions to the base pack here: https://github.com/Jimbno/UU-Tex.
Many sound effects were backported from the GregTech Community Edition Unofficial / Modern team: https://github.com/GregTechCEu/

Any new textures or reworked menus for Bartworks is soley the work of me (gears). This area may be changed if 

## Music duration metadata

The electric jukebox requires duration metadata to specify how many milliseconds each disk plays for.
These can be included in mods' jar resources under `soundmeta/durations.json`, or in the pack config directory at `config/soundmeta/durations.json`.
The format is a simple key-value map of sound IDs mapping to millisecond counts, and can be generated from the client automatically using `/gt dump_music_durations`.

```json
{
  "soundDurationsMs": {
    "minecraft:11": 71112,
    "minecraft:13": 178086,
    "minecraft:blocks": 345914
  }
}
```

## License

GT5-Unofficial-Extended is free software: you can redistribute it and/or modify it under the terms of the
GNU Lesser General Public License as published by the Free Software Foundation, either version 3
of the License, or (at your option) any later version.

GT5-Unofficial-Extended is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with GT5-Unofficial.
If not, see <http://www.gnu.org/licenses/>.
