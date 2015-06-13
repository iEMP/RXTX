# RXTX
rxtx-2.1-7r2 64bit for solaris

/*-------------------------------------------------------------------------
|   rxtx is a native interface to serial ports in java.
|   Copyright 1997-2004 by Trent Jarvi taj@www.linux.org.uk.
|
|   This library is free software; you can redistribute it and/or
|   modify it under the terms of the GNU Library General Public
|   License as published by the Free Software Foundation; either
|   version 2 of the License, or (at your option) any later version.
|
|   This library is distributed in the hope that it will be useful,
|   but WITHOUT ANY WARRANTY; without even the implied warranty of
|   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
|   Library General Public License for more details.
|
|   You should have received a copy of the GNU Library General Public
|   License along with this library; if not, write to the Free
|   Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
--------------------------------------------------------------------------*/
This is README  Fri Apr  5 13:05:27 EST 2015

See Also:

INSTALL:   install instructions and solutions to common problems
TODO:      Comments for developers
COPYING:   The LGPL license
PORTING:   hints for people trying to port rxtx
Authors:   who wrote what.
ChangeLog: when they wrote it.
RMISecurityManager.html:  Comments for people using RMISecurityManager 
SerialPortInstructions.txt:  HOWTO on read/writing to your com ports on linux for beginners

There are numerous possibilities for projects that involve serial communication.
Java is an excellent language for putting GUI apps together.  Well have fun.  
Send back stories. 

Copies of the latest RXTX will be on http://www.rxtx.org/download
The primary source for information/support is http://www.rxtx.org.
The rxtx mail-list is at Majordomo@hex.linuxgrrls.org.
Send email with "subscribe rxtx" in the subject without the quotes to join. 

This is a native lib for jdk 1.1.* and newer.  If you find changes required
for different platforms or OS's please pass them back this way so we may share
it with others.  Credit will be given unless one specifically requests no 
credit.

We chopped rxtx out of my program and tried to put a small example together.  
There is plenty of room for configurability, safe guarding and error reporting.
If you have some time please contribute some improvements.

We are interested in sharing this code in hopes that a more versatile lib may
be developed and released with minimal restrictions.  Please send any patches 
back my way if you like.

If you are interested in using rxtx for things like RS485, I2C or raw IO Please
get the latest CVS version.  Some work has been done for each of them.  The
latest development version is a stand alone implementation of CommAPI.

For bug reports please follow the directions in INSTALL

Trent Jarvi
taj@www.linux.org.uk
