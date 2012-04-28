.. index:: Differnece sidux™ debian-sid (EN)

========================================
Difference between sidux and debian/sid
========================================

Release |release| - |today|

Interesting differences for new users
======================================

* Newer kernel → better support of newer hardware
* sidux scripts/applications → making user's life simpler.
* sidux-paste (a pastebin tool for supporters)
* Ceni (interactiv konsole-networkmanager)
* fw-detect (detection of needed firmware)
* kernel-remover
* fll-iso2usb with qt-fll-iso2usb and install-usb-gui as front-ends
* Custom artwork. New artwork for each release.
* Latest software directly from one of the biggest (if not the biggest) package repository. (not a difference. just a point to mention)
* We provide support for sid. Debian does not.
* Fixes for broken packages in our repos. Help/support for d-u breakages.
* Warnings forum for (possible) d-u breakages.
* Fast system (no unnecessary services running).
* Fast install. (there is no installer for a sid system)
* Excellent manual. (again not really a difference, but daily updated, in 16 languages)


Interesting differences for seasoned (Debian) users
====================================================

Actual distribution based on sid (perhaps the biggest difference between sid/sidux):
-------------------------------------------------------------------------------------

* Enables the testing on a distribution level before packages enter testing (the place where Debian is tested as a distro)
* Easier to install since no dist-upgrade from testing/stable is needed to get sid
* Live and installable system on one ISO (easy to use custom build system but with no official support)
* Different runlevel configuration. Default is 5 (Debian is 3). Runlevels 2 3 4 stop X in Debian they dont.
* apt is recommended for package management. Official Debian recommendation is aptitude.
* Release every ~3 months
* Custom installer. Custom live init scripts / initramfs scripts (not that important but might be worth a mention)

Things that are special in sidux/Official recommendations
----------------------------------------------------------

.. I do not consider these to be differences but still things that should be mentioned to a potential new user especially if he is new to Linux

* ONLY apt for package management. NO GUIs, only for searching. NO aptitude
* Dist-upgrade always done with X stopped
* Read forums before you d-u
* NO support for any re-mastering tools (This is mostly a general reference in case user asks)

Differences between sidux and other Debian based distros
=========================================================

.. Most of the above differences hold. Additionally the below could be mentioned:

* sidux is a rolling distribution based on sid
* We follow the Debian policy and social contract and our packages are compatible with official Debian packages 

.. (Not sure if there are other such distros out there).
.. (this mostly has to do with Ubuntu based distros)

