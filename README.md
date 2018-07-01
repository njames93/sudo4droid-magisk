# Sudo4Droid Magisk Module

This module adds the sudo command to Android. It adds the file "/system/xbin/sudo", which is a script that passes all arguments to 'su -c'. Specifically, the code is 'su -c "$@"'.
The module source is on [Gitlab](https://gitlab.com/PorygonZRocks/sudo4droid-magisk.git).
