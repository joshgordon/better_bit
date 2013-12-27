A Better Bit 
============


This is Pebble's default "Just A Bit" watch face redone without the 10's place, 
and with flipped (actually flippable with a #define) endian-ness. 

Building
========
Firstly, install the pebble SDK on your computer and ensure it's in your path. Then run 

    pebble build 
    pebble install --phone <ip-of-your-phone> 

That's it, you should be up and running. 

Configuring
===========
There is one configuration option. Find `#define BIG_ENDIAN`. Removing this 
will flip the bit ordering. 
