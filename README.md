Enables free camera in places, and durning actions, that the game would normally not allow it.
Additionally, tries to eliminate unwanted camera snapping.
For use with Xenia that runs Ninja Gaiden 2, Xbox 360 game.

Free camera during:

	* ET/UT.
	* OT.
	* During environment static camera, otherwise. Eg. shaft clibing with jumps.
	* Opening Chests.
	* Off-the-wall downward strong attack.

Additional feature
---------------------
During gameplay, whenever there is free camera enabled by the Mod, holding LB or RT buttons would revert to the original camera mode. Normally, in game, these two buttons are used for 1st person camera control and for camera reset.

Requirements
-----------------
* CFF Explorer VII [CFF Explorer VII https://ntcore.com/explorer-suite/]
* Ability to attach DLL to the Xenia executable, either permanently dynamically.


Installation
--------------

This explains how to use CFF Explorer VII to add the DLL to the "xenia_canary.exe" file so it starts with the game automatically every time. Non-permanent way of starting the game is also possible, using dynamic DLL loading, eg. using a feature from Cheat Engine.

* Make sure you hav a backup of your "xenia_canary.exe" file.
* Copy "nx_owl_dll.dll" to the same folder/directory "xenia_canary.exe" is in.
* Start CFF Explorer VII.
* In the main menu select "File", then "Open" and browse for "xenia_canary.exe".
* From the list on the left, select "Import Adder".
* Int the middle of the main window. find and press the "Add" button.
* Browse and select "nx_owl_dll.dll".
* In the list below all the buttons, in the "Exported Functions" list, select its single item - if it's not selected already.
* Press "Import By Name" button.
* Press "Rebuild Import Table" button.
* Select main menu "File" then "Save" allowing the original file to be replaced.

