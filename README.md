ST_Anything
===========
Turn your Arduino into an AnyThing. ST_Anything is an Arduino library that works with your SmartThings ThingShield to create an all-in-one SmartThings device.

![screenshot](https://cloud.githubusercontent.com/assets/5153370/5604859/5da9edda-93a7-11e4-8e43-ce7a6d9cfa42.png)


## Overview
ST_Anything consists of three parts:
- The ST_Anything Arduino library
- A modified, more efficient version of the SmartThings (ThingShield) library
- The Groovy device script

## Setup Instructions
- Download the ST_Anything repository.
- Look inside the 'Arduino' folder of the repo.
- This folder structure should mirror that of your local Arduino directory. Copy all the files in the repo to the corresponding local directories (detailed instructions of this process are below if needed).
- Copy and paste the 'Sketches/ST_Anything/ST_Anything.ino' file into your local Arduino directory.
- Look inside the 'Arduino/libraries' folder of the repo.
- Copy and paste both the 'ST_Anything' and 'SmartThings' folders into your local 'Arduino/libraries' directory. (Note: it may be wise to rename your existing 'SmartThings' library to prevent any overwriting if you have already downloaded the official release)
- Add the groovy file ('Groovy/ST_Anything.groovy') to your SmartThings account online.
- Open the ST_Anything.ino

More instructions coming soon:

For now, reference the header files of the ST_Anything library for explanation of specific classes. 

Look at the documentation in the 'ST_Anything.ino' file for explanation of general use of the library.  
