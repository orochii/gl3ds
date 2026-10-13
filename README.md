# gl3ds
OpenGL compatibility layer for N3DS using [Libctru](https://github.com/devkitPro/libctru/).
Updated to work with current version of LIBCTRU (notice that even the name has changed).

Keep in mind this still doesn't work. It just compiles.

### Original description:
OpenGL implementation for the Nintendo 3DS using [ctrulib](https://github.com/smealum/ctrulib/).

This is mostly a port of Mesa 3D with unsupported features stripped.
A lot of portions are currently commented out temporarily until it
can either be implemented properly or deemed incompatible with
hardware or not simply worth implementing.

Mesa can be referenced here: [http://cgit.freedesktop.org/mesa/mesa/tree/src/mesa/main](http://cgit.freedesktop.org/mesa/mesa/tree/src/mesa/main)

## Requirements
- [DevkitARM](http://devkitpro.org/wiki/Getting_Started/devkitARM)
- [ctrulib](https://github.com/smealum/ctrulib/)

## Supported OpenGL API
List not yet compiled.

## Credit and Thanks
- [fincs](https://github.com/fincs) - GPU help
- [smealum](https://github.com/smealum) - ctrulib
- [cpp3ds](https://github.com/cpp3ds) - gl3ds
