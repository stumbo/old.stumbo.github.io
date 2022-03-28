+++
title= "Basic Components" 
subtitle= ""
date= ""
draft = false
weight = 500
+++

An implementation of the virtual machine (like a port of the microcode that turned the Xerox hardware into a lisp machine.) The emulator, called maiko, was initially developed at Fuji Xerox for the SunOS/SPARC. It was subsequently ported to many different OS and hardware combinations.

The Lisp system itself was split into layered parts:

    The core of the system written in Lisp to implement system components including memory management, Interlisp and Common Lisp interpreters and compilers.
    Basic operating system components: thread scheduler, drivers for disk, floppy, display, keyboard; windows, menus, fonts, networking (originally PUP, then XNS, then TCP/IP).
    The Library contains additional utilities and the development environment, text editor (TEdit), debugger, source file manager, email client,etc.
    LispUsers packages were contributed by users but curated by the Interlisp developer group
    Raster image Fonts in display and print resolution
    Documentation and release notes
    Memory images (sysouts) that can be loaded run without loading or compiling anything other than compatible maiko.



Releases



History

