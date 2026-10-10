# Raycaster

Raycasting demos (untextured and textured) based on Lode Vandevenne's
tutorial: https://lodev.org/cgtutor/raycasting.html

Uses the QuickCG library and SDL 1.2.

## Build (MSYS2 MINGW64)
g++ textured.cpp quickcg.cpp -o textured.exe $(sdl-config --cflags --libs) -std=c++11 -O1
