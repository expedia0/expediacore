
Debian
====================
This directory contains files used to package expediad/expedia-qt
for Debian-based Linux systems. If you compile expediad/expedia-qt yourself, there are some useful files here.

## expedia: URI support ##


expedia-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install expedia-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your expediaqt binary to `/usr/bin`
and the `../../share/pixmaps/expedia128.png` to `/usr/share/pixmaps`

expedia-qt.protocol (KDE)

