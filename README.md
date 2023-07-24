# WangED Project Archive

[![Discord](https://discordapp.com/api/guilds/521180240542826496/widget.png?style=shield)](https://discord.gg/HwDTssf)

This repository is an archive of all `.wep` (WangED Project) files that have been (accidentally?) included in Pangya patches.

## What are `.wep` files?

`.wep` files, internally referred to as "WangED project files", are files that define single course stages in Pangya.

Roughly, these files define the following:
* The textures a course is using
* All models (Puppets / `.pet`)
* In-game cameras
* Playfield areas
* Miscellaneous node collections

These files are, while still referenced in some places, most likely a legacy file format and are succeeded by `.gbin` files, which start with
the magic value `WEPX`, probably meaning **W**ang**E**D **P**roject E**x**tended.

Currently, two versions of `.wep` files have been found, according to the header present in the files:

* `#WEP V1.20 for Pangya`
* `#WEP V1.30 for Pangya`

## File Structure

The found `.wep` files are placed in the same structure as they have been found in the `.pak` files.

## Contributing

Do you have more `.wep` files that we missed? Feel free to open a Pull Request and request addition of the files to this archive.

If you have other info that you want to share with the community, feel free to head to the [Retreev Discord server](https://discord.gg/HwDTssf).