# BigMcLighting

A LED-Lamp in Burger/PUCK Design.

You need:
* one WeMos D1 Mini
* one microswitch 6x6x13mm
* a piece of twelve LEDs from a SK6812 (RGBNW) LED strip with 60 LEDs/m
* one powerplug
* one powesupply with at least 5v 1amp
* a kit of our lamp body

Now you have to solder it like in schematics:
![SCHEMATICS](https://raw.github.com/FabLab-Luenen/BigMcLighting/master/pictures/schematics.jpg)

Now Install the Software:

Download Repo from https://github.com/FabLab-Luenen/McLighting.

Replace the definitions.h in McLighting/Arduino with those of this repo.

Replace the data directory in McLighting/Arduino with those of this repo.

Load it into Arduino IDE and install all libraries referenced in https://github.com/FabLab-Luenen/McLighting.

Apply settings as shown:

![SETTINGS](https://raw.github.com/FabLab-Luenen/BigMcLighting/master/pictures/settings.jpg)

Upload sketch to WeMos.

Connect to the AP of the lamp.

Select your wlan and connect to it.

Open http://[ip_of_lamp]/upload in your browser.

Upload all files within the data folder.

If you assembled it all correctly it should look like this:

![RESULT1](https://raw.github.com/FabLab-Luenen/BigMcLighting/master/pictures/result1.jpg)

and work like this:

![RESULT2](https://raw.github.com/FabLab-Luenen/BigMcLighting/master/pictures/result2.gif)

and this:

![RESULT3](https://raw.github.com/FabLab-Luenen/BigMcLighting/master/pictures/result3.gif)

You can support us with a donation

[![paypal](https://www.paypalobjects.com/en_US/DE/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KNJ2WK3V5Y32Q)
