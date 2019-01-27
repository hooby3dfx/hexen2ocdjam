This is a Hexen 2 level (not quite a mod) inspired by the theme “What does home mean” for the 2019 Global Game Jam.

The level was created in TrenchBroom. 

To play it you will need a copy of Hexen 2. It is recommended to play with the “Hammer of Thyrion” open source Hexen 2 port. 

Extract the “ocdjam” folder into your Hexen 2 directory. To launch the game, run this command line:
glh2.exe -game ocdjam +map house03


Jammers:
-Bryan Barnes “hooby3dfx”
-Matt
-Austin
-Dan
-Jim



Technical notes:
-To edit/"build" the game...
	-The level can be edited in TrenchBroom
	-To see the textures, acquire a Hexen2 wad file and add the texture collection in the 'Face' menu
	-Add compile steps to TrenchBroom to run qbsp and light on the map
	-Edit the Hexen2.fgd file included with TrenchBroom to add the mod entities
	-Use hcc (included with Hammer port utils) in the src/qc folder to compile the QuakeC code with our entities
	-Use QuArK to view the pak0.pak file (and put the .mdl models in there)
	-Use the Blender Quake MDL export addon to export models with textures to mdl files
	-Strings are in the strings.txt file, and referenced by line number



Bugs:
-The secret teleporter isn't working

