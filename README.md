# Karbon
Carbon dioxide sensor system for sustainable forests

An ECE 198 Project by Steven Mu and Navtaj Hundal

![bot](title_graphic.png)

## What It Is
Karbon is a network of systems that makes use of bluetooth technology to relay information in case of a carbon dioxide surplus in a certain area. The user will place these devices sparsely around a forested area. From there, the network is complete, and will ping the user through a mobile android app once every minute with the carbon details. Based on those levels, we can determine whether if there's a surplus of carbon dioxide in the area (indicating an inefficient forest), or if there's a huge amount of carbon dioxide (indicating a possible fire).


## How is it made
We used an STM32 Nucleo board, a carbon dioxide sensor, as well as a custom 3d-printed shell to build our product. It is designed with weather in mind - so that the Karbon network can survive the harsest of climates. We used MIT app inventor for the android application.


## Revision History
REVISION 1 (Nov 5th 2022):
- Redo hardware code to include LCD testing
- add lcd.h and lcd.c


REVISION 2 (Nov 12th 2022):
- Finish hardware code to include sensor and bluetooth
- added sensor reads and bluetooth write functionanlities to the code


REVISION 3 (Nov 19st 2022):
- First version of app
- Prototype code added


REVISION 4 (Nov 20th 2022):
- Final version of app
- final code added
