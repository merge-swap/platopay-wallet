
Debian
====================
This directory contains files used to package platopayd/platopay-qt
for Debian-based Linux systems. If you compile platopayd/platopay-qt yourself, there are some useful files here.

## platopay: URI support ##


platopay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install platopay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your platopay-qt binary to `/usr/bin`
and the `../../share/pixmaps/platopay128.png` to `/usr/share/pixmaps`

platopay-qt.protocol (KDE)

