
Debian
====================
This directory contains files used to package mnprod/mnpro-qt
for Debian-based Linux systems. If you compile mnprod/mnpro-qt yourself, there are some useful files here.

## mnpro: URI support ##


mnpro-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mnpro-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mnproqt binary to `/usr/bin`
and the `../../share/pixmaps/mnpro128.png` to `/usr/share/pixmaps`

mnpro-qt.protocol (KDE)

