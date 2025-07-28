<div align="center">

![banner|800x300](./images/banner.png)

</div>

A guide on how to **download** and **install mods** in **Sons of The Forest** on PC. We've included instructions for downloading mods from [sotf-mods](https://sotf-mods.com), [Thunderstore](https://thunderstore.io), and [Nexus Mods](https://nexusmods.com) along with instructions on how to use their mod managers to install mods.

This guide is focused on **Windows users**, but some modding approaches should also work on Linux through **Steam Proton** or **Wine** with additional setup.

Whether you want to enhance survival mechanics, add QOL improvements, or create absolute chaos in the forest, this guide will give you an understanding on how to download and install mods.

## Table Of Contents
* [Requirements](#requirements)
* [Game Version Notes](#game-version-notes)
* [Backup Your Game Files!](#backup-your-game-files)
* [Modding Options Overview](#modding-options-overview)
    * [RedLoader + sotf-mods](#redloader--sotf-mods)
    * [Thunderstore + r2modman](#thunderstore--r2modman)
    * [Nexus Mods + Vortex](#nexus-mods--vortex)
    * [Manual Installation (Advanced)](#manual-installation-advanced)
* [Option 1: RedLoader + sotf-mods](#option-1-redloader--sotf-mods)    
* [Option 2: Thunderstore + r2modman](#option-2-thunderstore--r2modman)
* [Option 3: Nexus Mods + Vortex](#option-3-nexus-mods--vortex)
* [Option 4: Manual Mod Installation](#option-4-manual-mod-installation)
* [Uninstalling Mods / Restoring Game](#uninstalling-mods--restoring-game)
    * [Redloader](#redloader)
    * [r2modman](#r2modman)
    * [Vortex](#vortex)
    * [Manual](#manual)
* [Common Mod Types](#common-mod-types)
* [Conclusion](#conclusion)
* [See Also](#see-also)

## Requirements
* Sons of The Forest installed via **Steam**
* [7-Zip](https://www.7-zip.org/) or similar archive extraction tool
* Internet connection
* Basic folder and file navigation skills on Windows

## Game Version Notes
Sons of The Forest is under **active development**, meaning mods may break or require updates after official patches.

* Most mods are compatible with the **latest Steam version**.
* Always read the mod description to ensure compatibility with your game version.
* Avoid using mods in multiplayer unless the mod **explicitly supports it**. Otherwise, you may risk desyncs or bans.

## Backup Your Game Files!
Before installing any mods, it's best to back up your game files.

When backing up your game files, make sure to store them in a safe location that you'll remember (e.g. desktop).

Here are the game file locations.
* **Steam**: `C:\Program Files (x86)\Steam\steamapps\common\Sons Of The Forest`

Here are the save locations.
   * `C:\Users\<YourUser>\AppData\LocalLow\Endnight\SonsOfTheForest\Saves`

## Modding Options Overview
There are **three main ways** to mod Sons of The Forest.

### RedLoader + sotf-mods
[RedLoader](https://github.com/ToniMacaroni/RedLoader) is an open source mod loader.

To find mods to install with this mod loader, you'll want to browse mods from [sotf-mods.com](https://sotf-mods.com/) and make an account there.

### Thunderstore + r2modman
[Thunderstore](https://thunderstore.io/c/sons-of-the-forest/) is a popular source for mods in Sons of The Forest. Additionally, [`r2modman`](https://thunderstore.io/c/sons-of-the-forest/p/ebkr/r2modman/) is a popular mod manager you can use to install most mods from Thunderstore.

If you're interested in this option, make sure to make an account on Thunderstore!

### Nexus Mods + Vortex
You can also use [Vortex](https://www.nexusmods.com/about/vortex), a very popular mod manager tool from [Nexus Mods](https://nexusmods.com), to install mods in Sons of The Forest.

Make sure you make an account on Nexus Mods if you want to use Vortex!

### Manual Installation (Advanced)
Some users may prefer manually installing mods or a mod specifically requires a manual installation. In either case, this method not recommended for beginners.

## Option 1: RedLoader + sotf-mods
If you'd like to use [RedLoader](https://www.nexusmods.com/sonsoftheforest/mods/115) to install mods from [sotf-mods](https://sotf-mods.com), please perform the following steps.

1. Download RedLoader from GitHub [here](https://github.com/ToniMacaroni/RedLoader/releases).
2. Unzip the downloaded file using built-in Windows extraction tool or 7-Zip.
3. All contents from unzipped file should now be copied to Sons of The Forest's main game location (the `_RedLoader` folder should end up being in the same directory as `SonsOfTheForest.exe` executable).
4. Find a mod from [sotf-mods.com](https://sotf-mods.com), go to its page, and if the **Install with Red Manager** button isn't grayed out, click it.
5. The RedLoader tool should now pop up and add the mod.
6. Launch Sons of The Forest and test out your newly installed mods!

## Option 2: Thunderstore + r2modman
To browse and find mods from [Thunderstore](https://thunderstore.io/c/sons-of-the-forest/) and install them using [`r2modman`](https://thunderstore.io/c/sons-of-the-forest/p/ebkr/r2modman/), please follow the below steps.

1. Download `r2modman` from [here](https://thunderstore.io/c/sons-of-the-forest/p/ebkr/r2modman/).
2. Launch the tool and select **Sons of The Forest** as the game.
3. Click **Select Profile** (you can make multiple profiles).
4. Browse mods via [Thunderstore](https://thunderstore.io/c/sons-of-the-forest/) and click **Download** or **Install with Mod Manager**.
5. Click **Start Modded** in the top right to launch the game with mods.

## Option 3: Nexus Mods + Vortex
To browse and find mods from [Nexus Mods](https://www.nexusmods.com/games/sonsoftheforest) and install them using [Vortex](https://www.nexusmods.com/about/vortex), please follow the below steps.

Firstly, you'll want to download Vortex.

1. Download Vortex from [here](https://www.nexusmods.com/site/mods/1?tab=files).
    * Unless if you're a premium user, you will need to choose the **slow download** option.
2. Run the installer.
    * **Windows**: Ensure you have [.NET Desktop Runtime 6](https://aka.ms/dotnet/6.0/windowsdesktop-runtime-win-x64.exe) installed!
    * Vortex may prompt and guide you on fixing issues.
3. Now go to the **Games**  tab.
4. Either find Sons of the Forest from the **Unmanaged** list of games or search for it in the search box at the top.
5. Click the **Manage** button located in the middle of the Sons of the Forest game card.
6. This will attempt to add support for the game.
    * If Vortex has issues finding the game's location, follow the below steps:
        1. Go to the **Games** tab through Vortex.
        2. Find the game card under the **Managed** list.
        3. Click the **three dots** button located to the top-right of the card.
        4. Click **Manually Set Location**.
        5. Select the location of your game install.
    * Ensure you see the game's section in the left sidebar. If not, click the **Activate** button under the game card.

Now, you'll want to download and install mods!

1. Ensure you're logged into your Nexus Mods account through Vortex.
    * You can click the **Login** button at the top-right of the application if not.
3. Go to the mod's page you want to install on Nexus Mods' website.
4. If Vortex is supported, you'll see a **Vortex** button next to the **Manual** button on the right side. Click this button.
    * If you don't see a Vortex button, it means the mod is **not supported** through Vortex and you'll need to **manually install** the mod (instructions included below).
5. Choose what download type you want (e.g., slow download).
6. The file should open in Vortex automatically and start downloading.
    * Go to the **Downloads** tab through Vortex to check the progress!
7. The mod should be automatically installed.
    * You can go to the **Mods** tab under the Sons of the Forest section in the left sidebar to confirm if the mod is loaded.
    * You can remove mods by clicking the **Remove** button located on the right side of the mod item.

**NOTE** - Vortex may not handle dependency installations as smoothly as Thunderstore.

## Option 4: Manual Mod Installation
To manually install mods, please follow the below steps.

1. Download the mod manually from Thunderstore or Nexus.
2. Extract the archive with [7-Zip](https://www.7-zip.org/) or a similar program.
3. Copy mod files to the appropriate game folder, usually:
   * **Steam**: `C:\Program Files (x86)\Steam\steamapps\common\Sons Of The Forest\mods`
   * **With BepInEx**: `/Sons Of The Forest/BepInEx/plugins` (if the mod uses BepInEx)
4. If you don’t have BepInEx installed, but want it:
   * Download it from [Thunderstore](https://thunderstore.io/c/sons-of-the-forest/p/BepInEx/BepInExPack_IL2CPP/)
   * Extract into your game folder
5. Run the game (with Anti-Cheat disabled) to load mods.

**WARNING** - Always read the mod’s README! Some require specific folder placements or dependencies.

## Uninstalling Mods / Restoring Game
### RedLoader
* Remove the mod within the RedLoader UI and reload the game

### r2modman
* Use the profile manager to disable or delete mods
* You can create a “vanilla” profile with no mods

### Vortex
* You can remove mods by navigating to the **Mods** tab under the Sons of the Forest section, finding the mod within the list, and clicking **Remove** or **Disable** (under drop-down).

### Manual
* Delete files from mod manually
* Or verify files via Steam if issues arise:
    * Right-click game in Steam → Properties → Installed Files → **Verify integrity of game files**

## Common Mod Types
Here are some popular mod categories for Sons of The Forest!

* **Gameplay Tweaks** - God mode, infinite stamina, item unlockers
* **Quality of Life** - Better inventory, flashlight upgrades, keybind tweaks
* **Cosmetic Mods** - Custom textures, models, UI changes
* **Multiplayer Tools** - Map markers, GPS sharing, player tracking
* **Cheat/Trainer Mods** - For sandbox-style or experimental play

**NOTE** - Many mods require **BepInEx** as a base framework.

## Conclusion
By now, you have a basic understanding of how to download and install mods in Sons of The Forest using various methods.

You should now be ready to explore the wild world of **Sons of The Forest mods** and its mods!

## See Also
* [sotf-mods](https://sotf-mods.com)
* [Thunderstore - Sons of The Forest](https://thunderstore.io/c/sons-of-the-forest/)
* [Nexus Mods - Sons of The Forest](https://www.nexusmods.com/sonsoftheforest)
* [BepInEx Framework](https://thunderstore.io/c/sons-of-the-forest/p/BepInEx/BepInExPack_IL2CPP/)
* [RedLoader](https://github.com/ToniMacaroni/RedLoader)
* [r2modman GitHub](https://github.com/ebkr/r2modmanPlus)
* [Vortex](https://www.nexusmods.com/about/vortex)
* [Steam Community Discussions](https://steamcommunity.com/app/1326470/discussions/)

This guide will be updated and improved on over time. If you see any improvements that can be made, please feel free to reach out!