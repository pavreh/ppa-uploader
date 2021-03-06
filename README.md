# Deb Cup
GTK+ GUI tool for creating deb packages and uploading to a PPA.

## Screenshot
![deb-cup main window](/git_files/deb-cup-screenshot.png?raw=true)

## What Deb Cup can do
* Create the debian folder with template files and an empty install file
* Import patch
* Create an original source package
* Increment changelog
* **Create and install a dummy package with build dependencies**
* Create and install .deb binary package
* Create signed dsc and changes files (needed for uploading to a PPA)
* Send packages to a PPA

## Known issues
* **Issue:** debsign: Must be run from top of source dir or a .changes
  file given as arg.
  **Solution:** Import a GPG key.


## Download and Install
Supported operating systems
* Ubuntu 18.04 Bionic
* Ubuntu 17.10 Artful
* Ubuntu 16.04 Xenial
* Linux Mint 19
* Linux Mint 18

Operating systems which are not mentioned here are not tested. Deb Cup need not work properly with them.

[![Packaging status](https://repology.org/badge/vertical-allrepos/deb-cup.svg)](https://repology.org/metapackage/deb-cup)

[PPA](https://launchpad.net/~pavreh/+archive/ubuntu/ppa) `` `` 0.9.0
