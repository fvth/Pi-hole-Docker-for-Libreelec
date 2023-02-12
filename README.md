# Pi-hole-Docker-for-Libreelec

Docker addon with for Libreelec with official latest Pi-hole.

Based on old Linuxserver.io addon.

Default password is admin. Set 'permit all origins' in the settings (will be a bug fix soon).

Other known bugs, to be fixed:
- On reboot service doesn't start.
 Fix: fix path name
- On update losses lists.
 Fix: use docker cp to backup and restore FTL conf & db.

Be patient with the installation. The pull request takes time.
