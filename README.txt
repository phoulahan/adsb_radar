RADAR_OO_V1 - Windows 10 version

This is a project to display ADSB traffic captured using
an inexpensive European TV tuner USB dongle.

*** dump1090 must already be installed and working

It relies on dump1090 being installed so it can parse dump1090 decoded packets and display them in a pseudo-radar display.

[dump1090 is available from: https://github.com/antirez/dump1090]


Disclaimer: This software is provided for entertainment and educational purposes only. The user installs it on their systems at their own risk and absolutely no claims are being made regarding its suitability or its likelihood to not do harm.

Quick overview:

The software is configured from a collection of configuration files that are largely self-explanatory.

When running, a variety of key strokes can be executed:

a: auto-center
When away from the default airport specified in the cfg files, this will calculate 
a new center based on averaging detected aircraft.

ctrl-mousedown: select a new center for the radar

n: toggle long form of airport names

h: for aircraft not being displayed because they are not broadcasting lat/long information,
show them in the inventory list on the left panel.

r: reset/redraw the screen

i: zoom in

o: zoom out

q: quit the program


Parameters

Some of the parameters in the configuration files can be modified, but care must be exercised when changing the screen layout dimensions.


Required files

The application needs various configuration and data files to be in the same directory - these are included with the release.







