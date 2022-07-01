# Keyboard layouts for MacOs 12.4 Monterey

## Installation

1. Download release zip file from [Releases](https://github.com/hrayr1996/Apple-Packages/releases/tag/Armenian-Keyboard-Layout-0.0.1). Or download repository as a zip file or clone it.
2. Unzip it if you've downloaded it as a zip file.
3. Open "Armenian.bundle" in Finder and install it.
    * Try to make double click on it
    * If it didn't work - try to copy the `Armenian.bundle` to the "/Library/Keyboard Layouts/" folder
4. Go to System Preferences -> Keybaord -> Input Sources (tab).
5. Click on the "+" icon (Left-Bottom corner of the window).
6. Find Armenian language and select it.
7. In the list select Հայերեն and click on Add.

Done!

## How to uninstall permanently

1. Remove the keyboard layout from System Preferences -> Keybaord -> Input Sources (tab).
2. Open terminal and use following commands:
```bash
cd Library/Keyboard\ Layouts
rm -rf Armenian.bundle
```

Done!
