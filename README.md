# winTox

Lightweight [Tox](https://github.com/irungentoo/ProjectTox-Core) client for Windows (other operating systems to be supported in the future)

## Screenshots
![test](https://raw.github.com/notsecure/winTox/master/images/winTox.png "winTox early build")


## Building

Something like this:

>windres icon.rc -O coff -o icon.res

>gcc -o winTox.exe *.c icon.res -lgdi32 -lmsimg32 -lopenal32 -ltoxav 

## Downloads

[https://wiki.tox.im/Binaries](https://wiki.tox.im/Binaries)

## Info



