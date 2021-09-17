Pu-239 Installer
==============

A simple bash script to install Pu-239, Percona XtraDB 8.0 or MariaDB 10.4, PHP7.4-FPM, nginx and all of their dependencies.  
If chosen, redis, memcached, APCu and GoAccess can be installed.
This script has been tested on clean Ubuntu 18.04 and 20.04 LTS servers.

#### Please log in, to your server, as a non-privileged user, NOT as root, to run this script.

To use:

```
wget --no-check-certificate https://raw.githubusercontent.com/stivi05/Pu-239-Installer/master/installer.sh -O installer.sh
nano installer.sh #edit the first few lines. Please pay attention to what you use as you will use these again.
sudo bash installer.sh
```

If you like this project, please consider supporting me on [Patreon](https://www.patreon.com/user?u=15795177) 
