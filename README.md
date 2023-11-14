# Wolfenstein/DOOM style software renderers
### Fork of [jdah](https://github.com/jdah) [doomenstein-3d](https://github.com/jdah/doomenstein-3d) \

![project screenshot](screen/image.png)

* `src/main_doom.c`: a DOOM-style software renderer
* `src/main_wolf.c`: a Wolfenstein 3D-style software renderer

# Building & Running

* `$ git clone --recurse-submodules https://github.com/ivannikovaleksej10/doomenstein-3d.git` 

**compile and install SDL:**

* `$ cd doomenstein-3d/lib/SDL`

**Windows with Visual Studio:**
* Read ./docs/README-visualc.md

**Windows with gcc, either native or cross-compiling:**
* Read the FAQ at https://wiki.libsdl.org/FAQWindows
* `$ ./configure; make; make install`

**macOS with Xcode:**
* Read docs/README-macosx.md

**macOS from the command line:**
* `$ ./configure; make; make install`

**Linux and other UNIX systems:**
* `$ ./configure; make; make install`

**After**
* `$ cd src`
* `$ gcc main_wolf.c -o wolf.exe -lSDL2 -lm`
