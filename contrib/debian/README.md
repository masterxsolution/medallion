
Debian
====================
This directory contains files used to package medalliond/medallion-qt
for Debian-based Linux systems. If you compile medalliond/medallion-qt yourself, there are some useful files here.

## medallion: URI support ##


medallion-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install medallion-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your medallionqt binary to `/usr/bin`
and the `../../share/pixmaps/medallion128.png` to `/usr/share/pixmaps`

medallion-qt.protocol (KDE)

