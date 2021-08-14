# dmenu
my build of dmenu patched

From [suckless.org](https://tools.suckless.org/dmenu),

```
dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
```

This build supports the following:

- `-bw` to control dmenu window border width
- `-c` to center dmenu window to middle of screen
- `-F` to enable fuzzy matching in dmenu
- `-P` to ignore data from `stdin` &amp; replace keyboard input with `*`'s
- Xresources integration:
    - dmenu.font for font or font set
    - dmenu.background for normal background color
    - dmenu.foreground for normal foreground color
    - dmenu.selbackground for selected background color
    - dmenu.selforeground for selected foreground color
