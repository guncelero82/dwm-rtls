DWM1001-DEV enclosures
======

This project provides 3D designs for printing enclosures for Decawave's [DWM1001-DEV](https://www.decawave.com/product/dwm1001-development-board/) board, that is also included in the [MDEK-1001](https://www.decawave.com/product/mdek1001-deployment-kit/) kits. Unlike the default enclosures in the MDEK-1001, the one provided here include a power switch for saving battery between demos, which was the main motivation behind such designs.

Provided 3 types of enclosures depending on the node's role in the RTLS network:

| Board Role         | Design Preview (using Onshape)                                                                                                                      | STL Files                                                                                                                                                       |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tag                | [decawave tag](https://cad.onshape.com/documents/fd7ce9fdb29d748f5defa234/w/6842b3f97fdc5a03c4ed2d9d/e/81a1e0ac1e68754e6e93d733)     | [Box](STL files/Tag/Part Studio 1 - Box.stl), [Top](STL files/Tag/Part Studio 1 - Top box.stl), [Clip](STL files/Tag/Part Studio 1 - Clip.stl)                  |
| Anchor + support   | [decawave anchors](https://cad.onshape.com/documents/68251a8b84ceac5ed12b3330/w/f88035677ebf678f7fee32a6/e/6d59dcbaddc39079ad2a7eb5) | [Box](STL files/Anchor/Part Studio 1 - Box.stl), [Top](STL files/Anchor/Part Studio 1 - Top box.stl), [Support](STL files/Anchor/Part Studio 1 - clip-support.stl) |
| RPI Gateway Bridge | [RPI box](https://cad.onshape.com/documents/366b745c4205c93ae10f22b1/w/22c4cd09f8028b4d7e4f3c80/e/2a6d5b5a874f616bdd29a945)          | [Box](STL files/Gateway-RPI/Box click - Box.stl), [Top](STL files/Gateway-RPI/Box click - Top box.stl)                                                          |

## Tag Enclosure
The Tag enclosure design fulfils the following requirements:

- **Compact**: The tag is powered by a slim Li-Ion battery to reduce the box size.
- **Portable**: a clip is printed to to allow attaching the tag to a mobile person or any other asset.
- **Switched**: a tiny power switch is used for power cycling the board

Of course, the tag can be charged without opening the box.

### Required components

- Lithium Ion Battery - 850mAh 3.7 V (eg. [PRT-13854](https://www.digikey.com/product-detail/es/sparkfun-electronics/PRT-13854/1568-1495-ND/6605201))
- ON/OFF Switch (eg. [PRK22J5DBBNN](https://www.digikey.com/product-detail/en/PRK22J5DBBNN/CH865-ND/1083858/?itemSeq=267199711)) 


### Assembly 

<img src=img/TAG_inside.JPG width="500">
<img src=img/TAG_front.JPG width="500">
<img src=img/TAG_isometric.JPG width="500">


## Anchor Enclosure
The Anchor enclosure design fulfils the following requirements:

- **Removable**: A support [piece](STL files/Anchor/Part Studio 1 - clip-support.stl) is first fixed on the wall using a double-side tape for instance. Then the anchor box sits on it !
- **Switched**: a tiny power switch is used for power cycling the board.

This design eases the process of battery swap and the anchor positioning since one first positon the supports (on the wall) and can, at any time, safely and easily remove/replace the boards.

### Required components

- Lithium Ion Battery type 16340 - 700mAh 3.7 V (eg. on [amazon](https://www.amazon.com/dp/B072NYPS1Q/ref=sspa_dk_detail_2?psc=1&pd_rd_i=B072NYPS1Q&pd_rd_w=A7MSL&pf_rd_p=f0dedbe2-13c8-4136-a746-4398ed93cf0f&pd_rd_wg=2dLBb&pf_rd_r=BSWN4GD41D76TKKHR9WS&pd_rd_r=734f1f99-0eb7-11e9-84bf-671441283cd1))
- ON/OFF Switch (eg. [PRK22J5DBBNN](https://www.digikey.com/product-detail/en/PRK22J5DBBNN/CH865-ND/1083858/?itemSeq=267199711)) 

### Assembly 
<img src=img/ANCHOR_inside.JPG width="500">
<img src=img/ANCHOR_front.JPG width="500">
<img src=img/ANCHOR_isometric.JPG width="500">


## RPI Gateway bridge
The DWM1001-DEV can also be configured as a bridge and connected via SPI to a Raspberry Pi host. This results in a gateway that interconnects the UWB network with internet. This design is simply an enclosure of a raspberry pi, and a DWM1001-dev shield. The RPI is fixed using 2 screws.

### Required components

- 1 Raspberry pi model 3B
- 2 screw M2x6

### Assembly 

<img src=img/GATEWAY_inside.JPG width="500">
<img src=img/GATEWAY_front.JPG width="500">
<img src=img/GATEWAY_isometric.JPG width="500">


_____
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
