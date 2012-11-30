FBSyncPC
========

A tool for syncing FBReader book positions between multiple systems.  See
http://forum.xda-developers.com/showthread.php?t=890982 for the server side and
Android client.

You will need to locate your .FBReader directory, on Linux systems it will be
in your home directory, on Windows systems it will be in My Documents, someone
should tell me what it is on OS X.

You will want to modify the sync.conf file and copy it to the .FBReader
directory, and then run fbsync.

fbsync requires perl, and the following perl modules:
DBI
DBD::SQLite
LWP
URI::Escape
File::HomeDir
File::Spec
Config::Std

Please see http://www.perl.org/get.html and
http://www.cpan.org/modules/INSTALL.html for getting and installing perl, and
the required perl modules.


FBSync PC is Copyright (C) 2012 Zephaniah E. Loss-Cutler-Hull.

FBSync PC is licenced under the GNU GPL version 2, please see the file GPL-2
for the full license.

(If you really want it under a different license, contact me and tell me why.)

FBSync PC is under no warranty, it may eat your FBReader database, make your
computer melt, or even cause you to start reading the Twilight series, and I'm
not responsible.
