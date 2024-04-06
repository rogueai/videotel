# Videotel TTM90/TL

> Disclaimer: I'm not AT ALL qualified in any electrical work, I've mainly cobbled together a circuit from bits and pieces of information I found online. Use this doc at your own risk, it might result in a fried ancient video terminal :)

- There are 2 different models of the Videotel TTM90: the "regular" one and the /TL, which has a serial port on the back and can be distinguished by the gray power button on the front panel.
- The serial port outputs 19V on my model, make sure to check yours just to be sure
- I'm connecting the DB9 serial to a PC via a RS232-to-USB converter, it can be easily found online.
- The schematics have been put together from different sources on the internet. To be fair, I'm not entirely sure _how_ I made it to work. Based on my napkin calculations, it shouldn't :) But for some reason, it does... The RS232-to-USB converter I've got might be doing some extra magic.

The circuit will basically convert the TTL signal to RS232.

Once the circuit is built you'll also need:
- A specific terminfo `mntl.ti` I've found here: https://raw.githubusercontent.com/renaudgweb/Minitel it can be installed with the tool `tic`
- `agetty` to establish the session, similarly to how it's done in the github repo above

I'll try to make this readme more detailed in the near future.


