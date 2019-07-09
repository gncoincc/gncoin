
Debian
====================
This directory contains files used to package gncoind/gncoin-qt
for Debian-based Linux systems. If you compile gncoind/gncoin-qt yourself, there are some useful files here.

## gncoin: URI support ##


gncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gncoinqt binary to `/usr/bin`
and the `../../share/pixmaps/gncoin128.png` to `/usr/share/pixmaps`

gncoin-qt.protocol (KDE)

