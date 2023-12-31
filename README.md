# GZDoomGUI
An GUI to Manage Weapons and Inventory in GZdoom

/////SETUP////////
Requires Zscript 4.7.0 or later (Which should translate to GZdoom 4.7.0)

Be aware that this hud only works properly with inventory items when altHUD option enabled in options and just under the max screen size (when screen has no UI this software breaks down and dosent manage inventory properly)

To use this software downkload it Uzip it then locate GzdoomGUI folder add it to a Zip Archive (zip not 7z or tar) and rename that archive to .pk3 then run with GZdoom in terminal or using a launcher. 

Be aware that this software overrides the player class an is not compatable with many weapon mods EX. Brutal doom, Guncaster etc.

/////KNOW ISSUES////////

-The dropdown is incredibly glitcy and essentialy nonfunctional

-Droping items/weapons does not spawn said item in the game world

-using right click on a weapon brings up a nonfunctional equip option

-sprite scaling is hardcoded and causes problems with the fist

-Currently only works with DOOM properly not heretic/hexen/strife

-the screen draws items at a hardcoded virtual resolution of 1280x720 therefore does not properly support 4x3, 5x4, 16x10 etc.
