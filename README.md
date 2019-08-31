Xenon - Warcraft III Garena Hack
=====

Things to know:
- Supports patch 1.26a
- Compatible with Microsoft Windows XP, Vista, 7, 8, 8.1 and 10
- Works in Single Player mode with Frozen Throne (not with Reign of Chaos)
- Undetected in all versions of Garena Plus
- Do not use Xenon and any other map hacks togheter

How to use:
- Simply copy the "Xenon.mix" to your Warcraft III directory.
Example: "C:\Program Files\Warcraft III"
- Use "Xenon.ini" to configure the features you want to turn on/off.
- "Xenon.ini" will be created once you have started Warcraft for the first time.
- You have to restart Warcraft for changes to take effect.

Features:
- Camera Distance Hack
- Color Invisibles:
Changes the color of invisible units to red.
- Damage Notifier
- Dream UI:
Shows AS/MS in numbers, also shows the HP/MP regen rate in numbers.
- Game Start Notifier
Activate the Warcraft window once the game has started.
- Gray HP Under Fog
- Instant Game Start
Removes the 5 seconds countdown before starting the game.
- Mana Bar
- Map Hack:
Bypass -ah in DotA Allstars
Enable Enable Trade/Resource View
Make Units Clickable
Remove FOG on Main Map - Player View
Remove FOG on Mini Map - Player View
Reveal Illusions
Reveal Invisibles
Reveal Units on Main Map
Reveal Units on Mini Map
Show Enemies Ping Signals
Show Runes
Show Skills/Cooldowns
- Roshan Notifier
- Rune Notifier
- Scoreboard Shortcut Key
- and so on...

HotKeys:
- F5:
Enable / Disable Map Hack
- F6
Toggle Fog of War
- F7
Enable / Disable WoodCutter !!!
- F8
Enable / Disable SafeClick
- Numpad +:
Camera Distance Zoom In
- Numpad -:
Camera Distance Zoom Out
- Numpad *:
Camera Distance Set to Default
- Tab:
Show / Hide Scoreboard (DotA)
- Backspace
Clear Screen

How to build the project:
1. Install Visual Studio 2010 C++ Express
2. Download or clone the Xenon source
3. Open Warcraft.sln (VS solution file) or Warcraft.vcxproj (VS project file)
4. Check if Release configuration is active
5. Build menu --> Rebuild solution
6. Optionally compare /Release/Xenon.mix file with its previous version. If you see only ~6 bytes changed in the header, you have successfully rebuilt the mod.

How to debug Xenon.mix:
1. In VS browse to Property Manager --> Debug|Win32 --> Warcraft
2. Open that Property Page
3. Under User Macros update the War3_path user macro with the path where your Warcraft 3 installation is found (or just edit Warcraft.props)
4. Rebuild Debug configuration
5. Set breakpoints where you want, etc
6. Debug menu --> Start debugging
7. Wait some moment, Warcraft 3 will startup with the debugger attached

Be aware that the debugging will overwrite Xenon.mix in the Warcraft 3 folder! (but it doesn't touch Xenon.ini)
