# Coco3AppleRGB

This card will interface the **Color Computer 3 RGB port** to an **AppleColor RGB Monitor (model A2M6014)**.  It was created and shared with the CoCo community.  The design is provided here for whatever purpose you would like: make for yourself, build, sell, or modify.

![Card (Top)](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/View-Top.PNG)

## Overview

The card was designed from an schematic from 1996 by Tomi Engdahl.  The circuit was modified to work with the AppleColor RGB Monitor. Here is the original schematic:

![Card (Top)](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Circuit.JPG)

I bread boarded this circuit and made modifications (shown in pencil) to get it to work with the Apple Monitor. 

![Card (Top)](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Breadboard.JPG)

With a bit of fiddling, I was able to achieve a display:

![Card (Top)](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Monitor-Setup.JPG)

The key to getting this to work was recognizing that the Apple Monitor needs a *composite* sync (CSYNC) in order to display.  The CoCo3 has separate horizontal and vertical sync signals.  This circuit will take those signals, flip them, and then interface them into a composite signal (show on the oscilloscope).  Here is the resulting schematic:

![Card (Top)](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Schematic.PNG)

## Design

The project was built in **Kicad** and has all the project files included.  You can get a copy of Kicad from https://www.kicad.org.

Kicad was also used to layout of the PCB, show here:

![PCB Layout](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/PCB-Layout.PNG)

The bill of material is straightforward and only contains easy to find parts.  At the time of writing the total board cost is under $7 USD.

![Pricing](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Pricing.PNG)

The finished board:

![PCB](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/FinishedPCB.JPEG)

## Case

This project also contains a 3D printable case design.  The case is in two parts: Top and Bottom.  No screws are needed as the bottom slides into the top part for a snug fit.

![Case](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Case-Exploded.PNG)

The case was designed using **DesignSpark Mechanical**.  This is a free design tool.  You can download the tool from https://www.rs-online.com/designspark/mechanical-software.  The design files are included in the Case folder.

Here are some photos of the finished case:

![Case](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Case.JPEG)
![Case](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Mounted.JPEG)
![Case](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Bottom.JPEG)
![Case](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/InCase.JPEG)

## Additional Parts

The adapter works very well and 80 column text is very legible. To complete the set you will need a **5VDC Power Adaptor with a 5.5mm x 2.5mm plug, center positive**.  You will also need a **10 pin ribbon cable** to connect to the underside of the CoCo3.

![Set](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/IMG_1044.JPEG)
![Connector](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Connector.JPG)
![CoCo3](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/InAction.JPG)

## Complete - Enjoy!

![Overview](https://github.com/mrojas36/Coco3AppleRGB/blob/main/Docs/Overview.JPG)

