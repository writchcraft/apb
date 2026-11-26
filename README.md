# writch's APB Reloaded Config 

> [!CAUTION]
> I take 0 responsibility for any harm done to your game or your account.  
> Adding customized files is always at your own risk!  
> All files shared should fall in line with what Little Orbit allows when it comes to customizing our game.  

---

## Installation

The config is split into parts, so you only install what you want.  
Every part has the same layout: open the folder and drag whatever is inside (**APBGame** and/or **Engine**) into your APB folder, replacing the files.

> [!Important]
> The localization files are **.GER**, so add `-Language=1031` to your APB launch options

> [!Tip]
>Your APB folder is usually found at:
>    - Drive:\Gamersfirst\APB Reloaded\
>    - Drive:\Steam\steamapps\common\APB Reloaded\

### Easy Install (everything)

Open the `EASY INSTALL` folder and drag **APBGame** and **Engine** into your APB folder, replacing the files. That's it.

It includes Core + Graphics + Keybinds + Transparent UI + Weapon Stats + Vehicle Stats + Mission Icons, with Garbage Collection set to **60**.

Want to pick and choose instead? Use the parts below.

### 1. Core (required)

| Folder | What it does |
|---|---|
| `Core` | Uncapped FPS, ragdolls, muzzle flash, Garbage Collection **60**, splash screen and the main localization (icons, colours, item weights, objective timers) |

Install **Core first**, then add any of the optional parts below.

### 2. Optional

| Folder | What it does |
|---|---|
| `Graphics` | My graphics presets (see [Graphic Presets](#graphic-presets)) |
| `Keybinds` | My keybinds + Push to Talk / Push for Privacy binds |
| `Transparent UI` | Transparent UI, and chat fades after 5 seconds |
| `Garbage Collection/GC 0 (Missions)` | Sets Garbage Collection to **0** for missions (Core uses 60 for customization) |
| `Garbage Collection/GC 60 (Customization)` | Switches Garbage Collection back to **60** |
| `Localization Addons/Weapon Stats` | Weapon stats in every weapon description |
| `Localization Addons/Vehicle Stats` | Vehicle stats in every vehicle description, including weight |
| `Localization Addons/Mission Icons` | Mission titles show equipment **icons** instead of text like `[Spray Can]` |

> [!Note]
> Skipping an add-on doesn't remove it if you installed it before. To go back to default, run **Repair** in the APB launcher, then install your chosen parts again

---

## Features

- Uncapped FPS
- Custom keybinds
- Muzzle Flash: **ON**
- NPC Ragdolls: **OFF**
- Player Ragdolls: **ON**
- Custom localization with icons and purple-to-red gradients
- Weapon stats in every weapon description (Time to Kill, Shots to Kill, Damage, Dropoff Range, Reload Time, etc.)
- Vehicle stats in every vehicle description, including **Vehicle Weight**
- Mission menu shows equipment **icons** instead of text (e.g. Spray Can, Wire Cutters, Battering Ram)
- Mission objectives show item weights and how long each objective takes
- Up to date with the latest Joker Store weapons
- VOIP / Push-to-Talk support
- Graphics presets with labelled changes
- Transparent and faster UI, chat fades out after 5 seconds
- Garbage Collection set to **60** by default

---

## Icons + Localization

> ### District tab is the **Reaper scythe tag**
> 
> <img width="219" height="74" alt="image" src="https://github.com/user-attachments/assets/a35f79dd-03f4-401a-9bab-e664b29f26be" />

> ### **Weapon list**
> 
> <img width="192" height="250" alt="image" src="https://github.com/user-attachments/assets/d2f1b74e-7e00-4e42-9f23-15321f62ebe4" />

> ### **Clothing list**
> 
> <img width="169" height="464" alt="image" src="https://github.com/user-attachments/assets/f1b819f4-b964-4139-a6ec-7d6f555519c7" />

> ### **Vehicle list**
> 
> <img width="206" height="126" alt="image" src="https://github.com/user-attachments/assets/ec04b128-b285-4a0f-ba8c-0a37fade2cf4" />

---

## Graphic Presets

| Preset | Description |
|---|---|
| **Minimal** | Clay + low poly |
| **Low** | Low poly w/ outline |
| **Medium** | **writch** (My main preset) |
| **High** | Lazer's medium preset |
| **Maximum** | Maximum visual quality |

> [!Note]
> the "outline" is caused by a visual bug where the sun and shadows are around player models, this causes an outline to appear around player models in some locations

---

## Garbage Collection

Customization (Default) = 60

Missions = 0 

To switch, install `Garbage Collection/GC 0 (Missions)` or `Garbage Collection/GC 60 (Customization)`.

Or change it yourself: open `Engine\Config\BaseEngine.ini`, CTRL+F, and change **TimeBetweenPurgingPendingKillObjects=60** -> **TimeBetweenPurgingPendingKillObjects=0**

<img width="488" height="124" alt="image" src="https://github.com/user-attachments/assets/dbefde53-71dc-4db7-9585-bf3dca350de5" />

---

## Credits

spells — Helping with the OG stepped colours

[AltShadow](https://github.com/altshadow69/apb-minimized) — Icon support

[Flaws](https://github.com/flawsv/apb) — No Ragdolls

[jmilos](https://www.youtube.com/@jmilosapb) — keybinds

[lazer](https://github.com/lvzxr/apb-cfg-loader) — Medium graphic preset (used for **High**) and answering my questions

[myamai](https://myamai.neocities.org/apb/localization) — Localization Spreadsheet

---
