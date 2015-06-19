A central repository for SDL on Wii.

You can [download](http://code.google.com/p/sdl-wii/downloads/list) the latest compiled SDL libraries, or compile the latest source yourself. If you are a developer and wish to contribute code back to the SDL port, please post on the Issues page or contact me directly to be added to the project.

If you use SDL in your project, please link back to this SVN (eg: on your own SVN repository), so that anyone interested in compiling your source or working on a different SDL project can find it.

## Usage: ##

  1. Ensure that you have [devkitPPC r24 and libogc 1.8.7](http://www.devkitpro.org) or higher installed. If you have an older version, completely uninstall it first.
  1. Download and copy the PPC [ported libraries](http://sourceforge.net/projects/devkitpro/files/portlibs) to your portlibs folder (on Windows this is c:\devkitPro\portlibs\ppc)
  1. Copy all of the [SDL files](http://code.google.com/p/sdl-wii/downloads/list) to the libogc folder (on Windows by default this is c:\devkitPro\libogc).

## Compiling: ##

  1. Ensure that you have [devkitPPC r24 and libogc 1.8.7](http://www.devkitpro.org) or higher installed.
  1. Download and copy the PPC [ported libraries](http://sourceforge.net/projects/devkitpro/files/portlibs) to your PPC portlibs folder (on Windows this is c:\devkitPro\portlibs\ppc)
  1. Download the latest source from [SVN](http://code.google.com/p/sdl-wii/source/checkout).
  1. Compile and install SDL by running 'make install'.