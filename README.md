This is an Outscale fork of SeaBIOS with few interesting branches and specific patches.

[![Project Archived](https://docs.outscale.com/fr/userguide/_images/Project-Archived-red.svg)](https://docs.outscale.com/en/userguide/Open-Source-Projects.html)

Welcome to the SeaBIOS project!  This project implements an X86 legacy
bios that is built with standard GNU tools.

Please see build and developer information at:

  http://seabios.org/Developer_Documentation

For the impatient, SeaBIOS is built for QEMU and tested on QEMU with:

  make
  qemu -bios out/bios.bin

SeaBIOS can be configured with kconfig.  To change the default
configuration one can run "make menuconfig" prior to running "make".

For other types of builds, and for more detailed developer
documentation, please see the online documentation listed above.
