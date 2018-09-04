
Debian
====================
This directory contains files used to package quantlabd/quantlab-qt
for Debian-based Linux systems. If you compile quantlabd/quantlab-qt yourself, there are some useful files here.

## quantlab: URI support ##


quantlab-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quantlab-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quantlabqt binary to `/usr/bin`
and the `../../share/pixmaps/quantlab128.png` to `/usr/share/pixmaps`

quantlab-qt.protocol (KDE)

