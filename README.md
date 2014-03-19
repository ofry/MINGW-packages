MINGW-packages
==============

Package scripts for MinGW-w64 targets to build under MSYS2.

To build these, run msys2_shell.bat then from the bash prompt.

    cd ${package-name}
    makepkg-mingw

To install the built package(s).

    pacman -U ${package-name}*.pkg.tar.xz
