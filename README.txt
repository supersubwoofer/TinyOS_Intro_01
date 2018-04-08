# Introduction to TinyOS, Contiki and TOSSIM simulator

## Prerequisites

1. VirtualBox
2. Instant Contiki
3. [TinyOS](https://github.com/tinyos/tinyos-main)

[Start Instant Contiki in VirtualBox and setup TinyOS](https://d18ky98rnyall9.cloudfront.net/WcURxDZJEeinvxKfGmYdOg_5a4f2950364911e88d8c1f85606e2cb9_TinyOS-Howto.pdf?Expires=1523145600&Signature=lJzzP8w8U4QfG3-NguXKtxjaYp3xdTC8ZmoBWmaiAOiBcnTJlfRxH-osZfcOseYdqTBKVFbIpVVDZLAmxSsQcby08MFbDKjZedmzMQvzGvGgK177qmNzYya2w748xzB0k1~EtDO21w3ChERghZdQL4cto6OJ~czegYm0iQys5sY_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

## Run Modified 'Blink' app

1. create new directory under folder tinyos-main
   $ mkdir MyApps
2. $ cd MyApps
3. $ git clone https://github.com/supersubwoofer/TinyOS_Intro_01.git
3. $ make micaz sim
4. $ python runblink.py

## Credit

README for Blink
Author/Contact: tinyos-help@millennium.berkeley.edu

Description:

Blink is a simple application that blinks the 3 mote LEDs. It tests
that the boot sequence and millisecond timers are working properly.
The three LEDs blink at 1Hz, 2Hz, and 4Hz. Because each is driven by
an independent timer, visual inspection can determine whether there are
bugs in the timer system that are causing drift. Note that this 
method is different than RadioCountToLeds, which fires a single timer
at a steady rate and uses the bottom three bits of a counter to display
on the LEDs.

Tools:

Known bugs/limitations:

None.


$Id: README.txt,v 1.4 2006-12-12 18:22:48 vlahan Exp $
