# Götterdämmerung II 3D-printer

![GD2](http://www.timeexpander.com/wordpress/wp-content/uploads/testprint1.jpg)

This is the second iteration of the Götterdämmerung. The following improvements have been made:
- Core XY'ish layout. 
- Dual 24V power. 
- Improved Z stage.
- Geared stepper extruder, using M2 type filament drive.
- Designed for using cable towing chains.

Suggestions for selecting necessary third party stuff for building a complete printer

- Use 24 V power. This will enable you to run the steppers faster and use thinner wires. Also use a separate power supply for the heated bed (driven via a solid state relay)
- Buy a decent hot end. E3D with a 0.8 mm nozzle (or bigger) works fine with this printer.
- Use glass fiber reinforced timing belts.
- Use low impedance steppers.

Rumba board (supports 24V) with DRV8825, configured for 1/16 microstepping works fine with this printer. 

This is a working design, but it is still in development. 

The printer frame is made of 40x40 mm aluminium extrusions and it is extremely rigid. All idlers use ball bearings and 
the combination of 12mm steel axis and linear bearings ensures a stable platform.
The design scales in X/Y/Z without changes to any printed parts.

Please note that there are no build instructions or tutorial at this point. I'll probably do a write up, once I start building another one :)

Other stuff that has been printed on this printer:

Dante bust (29 x 30 x 26 cm). 13 hours print with 0.8mm nozzle, 0.3mm layer height

![Dante](http://www.timeexpander.com/wordpress/wp-content/uploads/dante-590x355.jpg)

Strandbeest ( 80 x 50 x 45 cm). Theo Jansen linkage, but with parameters based on output from my own genetic algorithm). 80+ hours printing time.

![Strandbeest](http://www.timeexpander.com/wordpress/wp-content/uploads/Interior.jpg)

This design is made available under the under the Creative Commons Attribution-ShareAlike CC BY-SA license (https://creativecommons.org/licenses/by-sa/4.0/)

![License](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-sa.png)

Hans Jørgen Grimstad
www.TimeExpander.com
