---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Goodspeed Aerospace (GOOD)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Goodspeed Aerospace (GOOD)

[Home](./index.md)

This parts pack add-on is an assortment of vaguely stock-alike parts, most requiring no additional texture memory (they mostly have unique models, but reuse stock part textures to save memory and achieve a stock-alike look). I've been adding my own parts to the game for about a year, filling in holes needing to be filled but either weren't filled by other mods, or the other mods weren't stock-like, or required more memory. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `GoodspeedAerospace` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/GoodspeedAerospace`
* Extract the package's `GoodspeedAerospace/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/GoodspeedAerospace`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/GoodspeedAerospace`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/GoodspeedAerospace`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [GoodspeedAerospace]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Contracts]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      + [Plugins]
        ...
      * #.#.#.#.htm
      * changelog.md
      * CC-BY-NC-SA-4.0.txt
      * readme.htm
      * GoodspeedAerospace.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
