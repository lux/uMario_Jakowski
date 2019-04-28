# Les Frères Super Guy

![Les Frères Super Guy](https://raw.githubusercontent.com/lux/Super_Guy/master/les-freres-super-guy.png)

Par Alyson Shane et John Luxford. Basé sur uMario_Jakowski, un clone de Mario
en C++/SDL2 par Łukasz Jakowski.

---

Author: Łukasz Jakowski

WWW: http://lukaszjakowski.pl
Email: jakowskidev@gmail.com

EXE and DLL - Download: http://lukaszjakowski.pl/DL/uMario.zip

YouTube video: https://www.youtube.com/watch?v=jya5He7KFsE


It is my first game made in C++.

Visual Studio 2012
SDL Tutorials which I have used:
http://lazyfoo.net/tutorials/SDL/index.php


My Google Play account: https://play.google.com/store/apps/dev?id=4635849298843013993


## Build Pre-requisites

FreeBSD:

    $ pkg install cmake sdl2 sdl2_image sdl2_mixer

OS X (brew):

    $ brew install cmake sdl2 sdl2_image sdl2_mixer

## Building and running

    $ make build run

    # or

    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ ./uMario
