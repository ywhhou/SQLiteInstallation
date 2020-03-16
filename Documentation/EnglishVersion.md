## SQLite Installation Guide
To download SQLite, you open the [download page](https://sqlite.org/download.html) of SQLite official website. SQLite provides installation across platforms. This article is an guidence for installing SQLite on Mac, Windows and Linux.
### Mac OS 
1. SQLite is preinstalled in all the latest versions of Mac. To start SQLite, excute the command `sqlite3` in Terminal: 

     ```
     $ sqlite3
     SQLite version 3.24.0 2018-06-04 14:10:15
     Enter ".help" for usage hints.
     Connected to a transient in-memory database.
     Use ".open FILENAME" to reopen on a persistent database.
     sqlite> 
     ```
1. In case SQLite is not installed on your Mac OS X, visit the [download page](https://sqlite.org/download.html)  and download **sqlite-autoconf-3310100.tar.gz** from the Source Code section. 
1. Run the following commands in Terminal:
     ```
     $ cd downloads #or where you saved the tar file.
     $ tar xvfz sqlite-autoconf-3310100.tar.gz
     $ cd sqlite-autoconf-3310100
     $ ./configure --prefix=/usr/local
     $ make
     $ make install
     ```
     
1. To verify the installation, run ```sqlite3```:

     ```
     $ sqlite3
     SQLite version 3.31.1 2020-01-27 19:55:54
     Enter ".help" for usage hints.
     Connected to a transient in-memory database.
     Use ".open FILENAME" to reopen on a persistent database.
     sqlite> 
     ```
1. SQLite is now installed on your Mac.
 
