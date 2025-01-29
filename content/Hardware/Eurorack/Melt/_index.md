---
title: Dual Passive Rectifier
weight: 2
summary: |
  A simple, passive signal chopping device
---

# Melt
- HW Revision 1.0
- Price: $50
- Passive device, no power required

## Module Function: 
<img src="./meltPanel.png">

Melt is like a passive mult, but worse. Instead of a direct path between jacks, there are diodes in the way to act like check valves for voltage. The module has two copies of the same circuit, duplicated on the top half and bottom half of the module with two groups of three jacks. 

A routes to B and C via one diode each. The diodes are facing different directions, so any bi-polar input to A will pass its positive half out of B and its negative half out of C. 

The top A is normalled to the bottom A. 

Because the module is passive, it can be used backward as well, combining inputs at B and C to be output at A. 

## Suggested Patches: 
- Route a bi-polar audio rate signal into one of the "A" jacks and "B" and "C" jacks become a crunchy stereo-ified version of your mono input. 
- Route bi-polar CV into one of the "A" jacks to route the positive side of your wave to the "B" jack and the negative side of your wave to the "C" jack 
- Mix two CV or audio rate signals into the "B" and "C" jacks for a sliced up combination of the two out the "A" jack
- Create a mediocre panner by using a DC-coupled mixer to combine an audio rate signal with a bi-polar CV and use jacks "B" and "C" as your left and right panned outputs



