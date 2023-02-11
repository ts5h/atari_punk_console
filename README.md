# Atari Punk Console
An Atari Punk console with double NE555P chips.  
  
![photo](https://user-images.githubusercontent.com/1344010/218284498-e7b30b60-c53d-4126-88a7-cf01d768c7d0.jpg)


## Schematic
![Schematic](./schematic/schematic.png)

## Reference
https://sdiy.info/wiki/Atari_Punk_Console

## Note
To address the problem described in "Problems" above, where "With a pot turned down to minimum, because internally the 555 shorts pin 7 to ground during parts of the oscillation, there will be a short circuit across the battery.", a 330-ohm resistor is connected in series with each pot.  
    
It certainly affects the oscillator's frequency, but the effect on the audible range seems minor when experimented with it.

## LICENSE
[MIT License](./LICENSE)  
Originally designed by [Forrest Mims](https://en.wikipedia.org/wiki/Forrest_Mims) in the 1980s, and then named by Kaustic Machines.
