IDZBuild
========

A set of scripts for building Open Source Projects.

These are the scripts that were used to build the Ogg, Vorbis, Speex and FLAC precompiled libraries I made available previously.

This is currently a work in progress, so please use it with care.

idz_fw
------

idz_fw *basename* *libname* *header-dir*

will create a pseudo-framework wih name *basename*.framework using all the architecture specific *libname* files and copying header files from *header-dir*.

e.g. idz_fw Ogg libogg.a install-iPhoneOS-arm64/include/
