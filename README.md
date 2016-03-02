# MegaCore
An Arduino core for the ATmega64 and ATmega128, all running a [ported version of Optiboot](https://github.com/vanbwodonk/optiboot128). <br/> <br/>


## Supported microcontrollers:
* ATmega128*
* ATmega64*
 
(* All variants - A, L and so on)

#### Why add Arduino support for these microcontrollers?
* They're dirt cheap (can be bought for less than a dollar at AliExpress and Ebay)
* They're still hand solderable (The TQFP variant have 0.8mm pin pitch)
* They're been around for more than a decade, and can be found in a lot of different equipment
* They got 53 IO pins (vs 32 for the [MightyCore](https://github.com/MCUdude/MightyCore) compatible ones and 86 for the ATmega1280/2560)

##TODO
* ~~Compile bootloaders~~
* ~~create boards.txt file~~
* ~~upload platforms.txt~~
* ~~Create pins_arduino.h file~~
* Add libraries
* ~~ Upload core~~
* Heavy testing
* Create pinouts diagram like the MightyCore have
 
##Status
I'm still waiting for my ATmega128 development board to arrive, but atleast sketches compile without any compiler warnings or errors. Feel free to try!

