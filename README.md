# DiamondBlackjack
Hello everyone! I've spent the past 2 months working on blackjack in a style as similar to GTA:O as possible and I've decided that all servers should enjoy this so I'm releasing it!
 
[![N|Solid](https://i.gyazo.com/8d6087d72268cf1aebe5c8fec2218769.png)]()

Features:
* All networked with up to 16 players playing at the same time
* Works with OneSync & OneSync Infinity
* All the juicy stuff you'd expect from blackjack
* Optional fancy teleporter to enter diamond casino
* Fancy menu showing how to play blackjack like GTA:O thanks to RageUI!
* Dynamically configurable, ability to make any blackjack table playable

Notes:
* This is not linked to any framework and works natively, to add chips/money into your framework/gamemode complete the two functions named `tryTakeChips` and `giveChips` at the top of `sv_blackjack.lua`
* There is no splitting or double down at this time, may come in the future
* You will need the Diamond Casino interior - There might be one on the forums somewhere, I don't know if I'm allowed to link the one I used, but just search "diamond casino fivem" in youtube. The download link is in the description in the first video.

Videos:
https://streamable.com/fb5sg
https://streamable.com/7gm49

How to install:
1. Ensure you have a compatible Diamond Casino interior.
2. Download/clone my forked modified version of RageUI [https://github.com/rubbertoe98/RageUI](https://github.com/rubbertoe98/RageUI)
3. Download/clone the main repo https://github.com/rubbertoe98/DiamondBlackjack
4. Copy DiamondBlackjack into your resources/ folder
5. Copy the src from the RageUI repo into the DiamondBlackjack folder
6. Start your resource and don't go over 21!

How to add more tables:
1. Do /getcasinotable ingame near to the table you would like to add Blackjack to. (This should print some information in your F8)
2. Open cl_blackjack.lua and find cfg.blackjackTables.
3. Copying the format provided, insert the information as it is given to you in your F8
4. Restart your script and you should be able to play blackjack on that table

Credits:
* Thank you to RageUI for allowing the easy creation of the instructions & teleport menu
* Rockstar for the decompiled scripts :heart: 

My personal dev discord
https://discord.gg/dnZTpUh
