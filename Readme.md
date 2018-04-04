HAX OS : Let's Get Started :)
=============================

![HaxoOS](https://github.com/haxogenOS/Manifest/blob/hax-n/haxoslogo.jpg)


Haxogen OS on Social Media
======================
[![](https://github.com/haxogenOS/Manifest/blob/hax-n/telegram.png)](https://t.me/haxogenOS)

-------
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**Colt OS**](https://github.com/ColtOS)
-------

How to Build?
-------------

To initialize your local repository using the HaxOS trees, use a 
command like this:

```bash
  repo init -u git://github.com/haxogenOS/manifest.git -b hax-n
  
  Then to sync up:
----------------

```bash
  repo sync
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  brunch <device_name>
```

