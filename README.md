# Game Programming in C++ Code
This repository contains the source code for *Game Programming in C++* by Sanjay Madhav.

The source code for the chapters is released under the BSD 3-clause
license. See LICENSE for more detail. Note that this license does not apply to
the code in the External directory. Each External project is licensed separately.

# Building the Code
Notes from Lucas:
On the original book, Each chapter's code is tested and works on both Microsoft Windows and Apple macOS.

This fork compiles the code on Ubuntu 18.04 using Libsdl2; I'll push changes that are answers to the exercises. At least there's U buntu friendly code corresponding to this wonderful book.  

For an example to compile in bash for chapter 01
g++ Game.h Game.cpp Main.cpp -lSDL2


I hope this works on Ubuntu 18.04 (I'm not there yet):
Code for Chapter 7 and beyond uses the FMOD API for audio. This requires
a separate installation from (https://www.fmod.com/download). Download
and install version 1.09.x of the FMOD Studio API (newer versions are untested).
On Windows, install FMOD to the default directory. On Mac, copy the contents
of the FMOD package into External/FMOD.
