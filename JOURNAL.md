---
title: "Bat-Signal"
author: "Pratham Rupera"
description: "a bat signal"
created_at: "2026-11-17"
---


# November 17: Building the Schematic and assigning footprints
I spat out ideas from my mind today till i decided on the bat signal. I have planned to remove the copper layers and silkscreen in the shape of a bat in the center of a circle pcb. this will show the bare fiberglass on the bottom making it transparent. on the other side i'll add all the components with led in the center part to shine through. so with this in mind i went on to design the schematic. everything went well except i had somehow selected the wrong folder for the basic symbols so after spending around 15 mins trying to fix that i went on to the actual schematic where i put the battery with a switch and 100 ohm resistors connected to the leds. now i soon realised that i had reversed the leds pins and my circuit wouldnt work(thanks to fabricate-help). i fixed that and assigned the footprints with some googling here and there. and yeah 1 more thing. i plan to use 90 degree leds so they point towards the transparent screen and shines through.
![](1_1.png)
![](1_2.png)

** Time spent: 1hr **

# November 17(Part 2): Building the actual PCB and finishing it
So i went to pcb design and the problem i face head on in the starting is finding a bat symbol which is perfect for my board. after finding one and experimenting with sizes i figured out the best one and put it in its place. i love how it looks. after some searching that how to make the bare fiberglass show through i changed the layers on the image. then i carefully positioned the leds so it converges to one place and then shines through the board. i used a coin holder to hold 3v batteries which are easily available and also used resistors to operate the leds. and yeah a slide switch goes without saying. my board looks pretty cool now and i would say its ready to be exported and create the bom of the parts. but all that tmrw as i am pretty tired today.
![](2_1.png)
![](2_2.png)

** Time spent: 1hr **

# November 18: Finishing the project
i just realized i did a generational mess up. i wanted the whole circle to be under 6 cm but i selected the radius as 65mm just to realize that on jlcpcb when i saw the board size. so i went back to kicad and tweaked the radius of circle till all parts were fitting in(barely) and remade the gerber and drill files. i had to make all the connections again. then i went on robu to find the best parts for myself and created the bom and then installed jlcone to see the pricing of pcb since they cut so much price on desktop. i also made the thickness of the pcb lesser so the light can come out of the back. after i write this journal and commit i'll format the journal to make it look good and add images then write the readme and upload all gerber files.
![](3_1.png)
![](3_2.png)
![](3_3.png)

** Time spent: 1.5hr **
