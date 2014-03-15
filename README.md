kickstart
=========

Kickstart files for install CentOS quickly.

How to use it?
==============

- Download centos network ISO from http://mirror.centos.org/centos/6/isos/
- Boot from the ISO file
- On the boot screen press _TAB_ and write 'ks=_config-file.cfg_' at the end of configuration line
- Press enter and autmatic installation will start

Config file naming
==================

Config file names created this way:
 architecture-filesystem-root_size-swap_size-packages-lang.cfg

Kickstart files
===============

- *xen-lvm-all-auto-min_admin-hu.cfg*: Kickstart for XEN HVM with LVM. Root partotion will us all available space and swap will be 8GB. Basic admin tools and EPEL repo will be installed.

Root password
=============

During the installation _root_ will be set to _'tmppwd'_.