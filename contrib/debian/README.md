
Debian
====================
This directory contains files used to package orbitd/orbit-qt
for Debian-based Linux systems. If you compile orbitd/orbit-qt yourself, there are some useful files here.

## orbit: URI support ##


orbit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install orbit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your orbit-qt binary to `/usr/bin`
and the `../../share/pixmaps/orbit128.png` to `/usr/share/pixmaps`

orbit-qt.protocol (KDE)

