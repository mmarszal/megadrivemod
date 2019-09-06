Mega Drive Switchless Mod
=====================

This code is an adaption of the Saturn Switchless Mod (http://knzl.de/saturnmod/)
All credit goes to Sebastian Kienzl, and his original license is included here.

This PIC code has been modified to be somwhat simpler to modify for Mega Drives,
specifially for using Multi-bios ROM chips for the Mega CD.

The reason for this is many supplied Mega CD roms don't have a unified order,
therefore loading an incompatible bios that matches the Mega Drives region.

This code simply removes the unnecessary Saturn Jumper settings, and simply
focuses on setting RC0 and RC2 properly in order to get the correct
Mega CD bios loaded.

RA4/5 will be considered as an order change for future purposes.

For flashing a 16F630/16F676, you will only need the .hex-file, the rest is
the source-code needed for building it yourself.

Building
--------

For building it, you'll need:

 * Microchip MPLAB IDE (FREE)
 * HI-TECH C Compiler, you can use the free "lite" version or the demo
	(http://www.htsoft.com/microchip/products/compilers/PICClite.php)
 
License
-------

    Saturn Switchless Mod
    Copyright (C) 2004 Sebastian Kienzl
    
    This program is free software; you can redistribute it and/or
    modify it under the terms of the GNU General Public License
    as published by the Free Software Foundation; either version 2
    of the License, or (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

