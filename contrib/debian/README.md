
Debian
====================
This directory contains files used to package herbd/herb-qt
for Debian-based Linux systems. If you compile herbd/herb-qt yourself, there are some useful files here.

## herb: URI support ##


herb-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install herb-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your herbqt binary to `/usr/bin`
and the `../../share/pixmaps/herb128.png` to `/usr/share/pixmaps`

herb-qt.protocol (KDE)

