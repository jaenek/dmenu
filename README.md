# dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.

## Requirements
In order to build dmenu you need the Xlib header files.

## Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):
```
make clean install
```

## Running dmenu
See the man page for details.

## Patches
This source was modified and contains following patches:
* dmenu-mousesupport-4.7.diff - add mouse support

The keybindings have been modified so that you can move the cursor with:
* Ctrl-h - left
* Ctrl-l - right
* Ctrl-j - down
* Ctrl-k - up

Colors of dmenu are defined in `~/.cache/wal/colors-wal-dmenu.h` this allows for changing colors and recompiling without touching the source code