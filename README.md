# RippyUI v1.22

Collection of addons with slight modifications for Classic 1.13.x


<img src=images/RippyUIv1.2.png width=900>


### How to Install

Backup your old WTF and Interface Folder, put mine in their place.
To use custom fonts, rename "Fonts1" or "Fonts2" (whichever you want to use) to "Fonts" and place into your WoW Folder (Not Addons)

### How to keep your Keybinds and Macros

From your old WTF folder, take your bindings-cache.wtf and macros-cache.wtf and overwrite them in my WTF folder.
You can find bindings-cache.wtf and macros-cache.wtf inside the following two folders
1) WTF/Account/[ACCNAME] 
2) WTF/Account/[ACCNAME]/[ServerName]/[CharacterName] 

### First Run Guide

1) You have to resize the chat yourself.

2) Enemy nameplates by default aren't shown. You can enable in interface options or use default keybind V.

3) Your fivesecondrule(the blue bar that shows when your mana starts to regen after casting) is out of place, you need to reposition fivesecondrule. Use /fsr unlock to move, left click bar to move it right click bar to resize it.

4) Your castbar is default. You need to type /ecb and go to the profiles tab, select "rippy" and then press load.

### FAQ
How do I move the frames?

Leatrix -> Frames -> Enable Manage Frames -> Click cogwheel

### Addon List 
(Alot of these are modified by me, if you use a version that wasn't fixed by me it might not have the same functionality)

1) AlignFix - type /align to show a grid
2) BlueShamans - Recolors shaman class color to blue (was pink)
3) ClassicAuraDurations - Shows swipe timers on enemy debuffs, use with OmniCC to show number. (Requires LibClassicDurations) (Type /cad hooktarget if it isnt working)
4) ClassicCastbars - customizable addon to shows enemy cast bar
5) ClassicCodex - pfQuest port. this addon actually farms so hard /ClassicCodex 
6) eCastingBar - Cast bar /ecb 
7) FiveSecondRule - shows the 5 second rule after casting before mana regens, helpful for starting levels /fsr
8) HideRaidManager - Hides the annoying RaidManager until hovered over
9) Kui Nameplates - Customizable Nameplates
10) Leatrix_Maps - shows unexplored areas on map, shows dungeons
11) Leatrix_Plus - /ltp or click minimap button. Lazypig but with a million other useful things. This is the core of my addon pack/ui. Very useful and highly customizable
12) LibClassicDurations - Required by ClassicAuraDurations to show debuff times
13) Lorti-UI-Classic - reskin/texturize default frames/bars. Blackframe but with button textures
14) OmniCC - Cooldown Numbers
15) NugRunning - Nice visual bars for enemy debuffs. Works even if you untarget the mob. (You can also enable this to show a cooldown bar but I have it disabled by default) /nrun
16) MonkeyQuest - quest tracker replacement, default quest tracker only allows to track 5 quests at a time, also it looks better and it's more functional
17) OneBag3 - One bag to rule them all
18) RealMobHealth - Stores mob health info after killing a mob
19) RippyFont - Changes size of certain ingame fonts
20) RippyPortraits - Class Icon as Portraits, and a CUSTOM Player(Self) Portrait. Hover over your own portrait and scroll up and down with mousewheel to select your portrait you want to use.
21) TinyTooltip - customizable tooltip. /tt for options
22) tullaRange - colors action bars if no resources / out of range
23) TwitchEmotes - if you type twitch emotes in game it shows the emote. WidePeepoHappy 
24) UnitFramesImproved - the best unitframe addon ever developed. Removes "name bar" and add its to the "health bar", colors by classes, etc. /ufi
25) VendorPrice - shows vendor price, pressing left cntrl with bags open flashes the lowest value grey item, if you need to delete something quickly
26) SimpleMap - /smfade off to disable map fading while moving
### Changelog

1.22 added QuestXPTracker (Adds amount of XP every quest gives when you accept a quest). Added Bat portrait option

1.21 SimpleMap is back :)

1.2 Fixed a ton of compatibility issues (RealMobHealth finally works with UnitFramesImproved now!). Added custom fonts. Resized fonts. Added custom player portraits for yourself + class portraits for targets. Re-added NugRunning by request (Hopefully blizzard doesn't break the API again) 

1.11 Minor tweaks

1.1 Fixed Nameplate castbar, disabled buff textures, cleaned up compatibility issues and lua errors.

1.0 Made the UI.

