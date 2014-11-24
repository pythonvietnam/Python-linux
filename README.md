Python-linux
============

Cài đặt python trên Linux


A note about Debian / Ubuntu Linux user

Use the following command to search for available versions of Python under Debian and Ubuntu Linux:
$ apt-cache search python | egrep "^python2.[0-9] " --color
Type the following command to install python version 2.x:
$ sudo apt-get install python2.6
Type the following command to install python version 3.x:
$ sudo apt-get install python3.1
Sample outputs:

Reading package lists... Done
Building dependency tree
Reading state information... Done
The following extra packages will be installed:
  python3.1-minimal
Suggested packages:
  python3.1-doc python3.1-profiler
The following NEW packages will be installed:
  python3.1 python3.1-minimal
0 upgraded, 2 newly installed, 0 to remove and 13 not upgraded.
Need to get 5,444 kB of archives.
After this operation, 19.9 MB of additional disk space will be used.
Do you want to continue [Y/n]? y
Get:1 http://debian.osuosl.org/debian/ squeeze/main python3.1-minimal amd64 3.1.3-1 [1,669 kB]
Get:2 http://debian.osuosl.org/debian/ squeeze/main python3.1 amd64 3.1.3-1 [3,775 kB]
Fetched 5,444 kB in 27s (201 kB/s)
Selecting previously deselected package python3.1-minimal.
(Reading database ... 280220 files and directories currently installed.)
Unpacking python3.1-minimal (from .../python3.1-minimal_3.1.3-1_amd64.deb) ...
Selecting previously deselected package python3.1.
Unpacking python3.1 (from .../python3.1_3.1.3-1_amd64.deb) ...
Processing triggers for man-db ...
Processing triggers for menu ...
Processing triggers for desktop-file-utils ...
Processing triggers for gnome-menus ...
Setting up python3.1-minimal (3.1.3-1) ...
Setting up python3.1 (3.1.3-1) ...
Processing triggers for menu ...

A note about Red Hat/ RHEL / CentOS Linux user

Type the following command:
$ sudo yum install python
OR
# yum install python
How do I find out installed python version?

Type the following command:
$ python --version
Sample outputs:

Python 2.6.6
