# rf-ui releases

Downloads for **rf-ui** - a UI customization DLL (`dinput8.dll`) for the Cerberus RF Online client.
Get the latest zip from the [Releases](../../releases/latest) page.

## Installation

1. Close the game and the launcher.
2. Copy `dinput8.dll` into the client folder, where `RF_Online_4gb.bin` is located.
3. In the launcher settings, enable RFOnline 4gb - it won't work without it (for now).
4. Start the game as usual through the launcher.
5. After entering the world, a small 28x28 px button will appear in the bottom-right corner. `rf-ui.log` will appear in the client folder, and `rf-ui.ini` after the first setup.
6. Uninstall: close the game and delete `dinput8.dll` (and also `rf-ui.ini` and `rf-ui.log` if you don't need the settings).

If `rf-ui.log` says that the client is unknown and the features are disabled, you have a different client version: the mod does nothing and the game runs normally.

This repository contains release files only, no source code.
