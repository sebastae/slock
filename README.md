# Slock, a simple screen locker

Forked from https://git.suckless.org/slock/

## Changes

The changes in this repo adds an indicator for when Caps Lock is enabled by making the screen purple


Below the line is the original README

---

slock - simple screen locker
============================
simple screen locker utility for X.


Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


Running slock
-------------
Simply invoke the 'slock' command. To get out of it, enter your password.
