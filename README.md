Building a Text Editor in C

Currently learning low-level terminal programming in C by building a text editor inspired by the Kilo editor tutorial.

This repository documents my progress while learning:

raw terminal mode
keyboard input handling
terminal control with termios
low-level Linux programming
text editor internals

Environment:

Fedora WSL
GCC
Neovim

Current Progress

 Enable raw mode -
 Read keypresses byte-by-byte -
 Detect control characters -

 remain :
 Handle escape sequences
 Cursor movement
 Screen rendering
 Text buffer
 File saving
 Syntax highlighting

Current Demo

The current version reads keyboard input directly from the terminal and prints ASCII values of pressed keys.

Example:

97('a')
113('q')
127

Press q to exit.

Build

Compile:

gcc main.c -o kilo

Run:

./kilo

Learning Source

Inspired by:
Build Your Own Text Editor

Goal

The goal of this project is not just to copy a tutorial, but to understand how terminals and text editors work internally by building one step-by-step in C.
