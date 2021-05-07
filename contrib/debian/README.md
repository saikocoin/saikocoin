
Debian
====================
This directory contains files used to package saikod/saiko-qt
for Debian-based Linux systems. If you compile saikod/saiko-qt yourself, there are some useful files here.

## saiko: URI support ##


saiko-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install saiko-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your saiko-qt binary to `/usr/bin`
and the `../../share/pixmaps/saiko128.png` to `/usr/share/pixmaps`

saiko-qt.protocol (KDE)

