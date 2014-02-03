Compton (A compositor for X11)
------------------------------

Source download:
[https://github.com/chjj/compton/archive/v0.1_beta2.tar.gz](https://github.com/chjj/compton/archive/v0.1_beta2.tar.gz)
Make sure it is saved in the same directory as the build script and 
is named 'compton-0.1_beta1.tar.gz'.

Setting VERSION=git will automatically download 
and build the latest git version

Compton is a compositor for X, and a fork of xcompmgr-dana.

### Dependencies:
 
Slackware ships with most of these dependencies.
The only dependency not included with Slackware is libconfig.

__B__ for build-time __R__ for runtime

* libx11 (B,R)
* libxcomposite (B,R)
* libxdamage (B,R)
* libxfixes (B,R)
* libXext (B,R)
* libxrender (B,R)
* libXrandr (B,R)
* libXinerama (B,R) (Can be disabled with `NO_XINERAMA` at compile time)
* pkg-config (B)
* make (B)
* xproto / x11proto (B)
* sh (R)
* xprop,xwininfo / x11-utils (R)
* libpcre (B,R) (Can be disabled with `NO_REGEX_PCRE` at compile time)
* libconfig (B,R) (Can be disabled with `NO_LIBCONFIG` at compile time)
* libdrm (B) (Can be disabled with `NO_VSYNC_DRM` at compile time)
* libGL (B,R) (Can be disabled with `NO_VSYNC_OPENGL` at compile time)
* libdbus (B,R) (Can be disabled with `NO_DBUS` at compile time)
* asciidoc (B) (and docbook-xml-dtd-4.5, libxml-utils, libxslt, xsltproc, xmlto, etc. if your distro doesn't pull them in)

[https://github.com/chjj/compton](https://github.com/chjj/compton)
