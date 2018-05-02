
Debian
====================
This directory contains files used to package recryptd/recrypt-qt
for Debian-based Linux systems. If you compile recryptd/recrypt-qt yourself, there are some useful files here.

## recrypt: URI support ##


recrypt-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install recrypt-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your recrypt-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

recrypt-qt.protocol (KDE)

