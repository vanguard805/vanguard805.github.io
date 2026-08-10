# **PoE 2 Regex Builder**

**Version: v0.9.8**  
**Author: Vanguard805**

PoE 2 Regex Builder is a free Windows utility for creating compact search regex for Path of Exile 2. Instead of manually writing regex, select the item type and modifiers you want and the program generates a compact search string for you.  


## **Installation**

No installation is required.

- Download PoE2RegexBuilder.exe.
- Place it anywhere you would like.
- Run the executable.

Python, PySide, pip, a compiler, and the source code are not required.

**Windows SmartScreen:** Because the application is independently distributed and the executable may not be digitally signed, Windows may display a SmartScreen warning. A SmartScreen warning by itself does not mean the program has detected malware.  


## **How to Use**

1. Select a Category.
2. Select a Group.
3. Select the desired Type.
4. Choose a defense type where applicable, such as Armour, Evasion, or Energy Shield.
5. Check the modifiers you want.
6. Select a numeric mode when needed.
7. Choose the desired AND/OR combination.
8. Copy the generated regex.
9. Paste it into the appropriate Path of Exile 2 search field.
10. 

## **Numeric Search Modes**

- Generic — Finds the modifier regardless of its numeric roll.
- Exact — Searches for a specific value.
- At Least — Searches for the selected value or higher.
- At Most — Searches for the selected value or lower.
- Range — Searches between a specified minimum and maximum.

## **Compact Regex**

PoE 2 Regex Builder intentionally abbreviates modifier searches to conserve characters.

For example, instead of generating a long expression such as:

`Projectiles.*deal.*Damage.*Hits.*against`

the builder may generate something similar to:

`pr.*ag`

The application attempts to keep these expressions short while distinguishing them from other modifiers that can appear on the same item.  


## **Supported Content**

The builder includes support for a wide range of Path of Exile 2 equipment and search types, including:

- Body Armour
- Boots
- Gloves
- Helmets
- Shields and other Offhands
- Belts
- Rings
- Amulets
- Weapons
- Jewels
- Tablets
- Waystones
- Relics - Coming Soon

Base, Crafted, Desecrated, and other supported modifier pools are included where applicable.  


## **Modifier Updates**

The application includes support for refreshing supported modifier information from online data sources.  
Different numeric tiers of the same logical modifier are consolidated where appropriate. The program's numeric controls are used to specify the roll you want instead of displaying every tier as a separate checkbox.  


## **Reporting a Problem**

If you find an incorrect modifier, regex collision, missing modifier, or other problem, please include as much of the following as possible when reporting it:

- Application version
- Item category and type
- Modifier(s) selected
- Generated regex
- What the regex matched incorrectly or failed to match
- A screenshot, if possible  


## **License and Redistribution**

Copyright © 2026 Vanguard805. All rights reserved.  
PoE 2 Regex Builder is provided free of charge for personal and non-commercial use.  
You may download, use, copy, share, mirror, and redistribute the compiled application (.exe) without charge, provided that:
- The application is distributed unmodified.
- This copyright and license notice is retained.
- The application is not sold or redistributed for profit.
- The application is not presented or claimed as the work of another person or organization.
- Modification, reverse engineering, or creation and distribution of modified versions is not permitted without permission from Vanguard805.
- Permission to redistribute the compiled application does not transfer ownership of the software or its underlying source code.  


## **Warranty**

This software is provided "as is", without warranty of any kind, express or implied.  
The author is not responsible for damages, data loss, account actions, incorrect search results, game changes, or other consequences resulting from the use of this software.  
Use of the application is at the user's own discretion.  


## **Disclaimer**

PoE 2 Regex Builder is an independent, unofficial community tool.  
It is not affiliated with, endorsed by, sponsored by, or associated with Grinding Gear Games.  
Path of Exile and Path of Exile 2 are trademarks of Grinding Gear Games.
