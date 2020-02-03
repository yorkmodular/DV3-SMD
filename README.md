## York Modular DV3 - Dual AR Envelope Generator/Slew Limiter

This is the third iteration of my 'Drumvelope' AR module - the main improvement being that it now comes with twice as many envelope generators. That is, two instead of one ...

If you want a nice, simple envelope generator aimed at use in percussion patches then this is it. Better still, you can also use it as a slew limiter if you're so inclined - bear in mind, however, that the response is exponential, rather than linear.

### Construction notes
Other than being SMD, there are no particular gotchas associated with this build. 

The attack/release rates are controlled by capacitors C1 and C8 - for pre-built units I generally use 2.2μF caps, but this value isn't set in stone by any means. Higher values will lead to longer attack/release times, and vice versa, although using capacitors less than 1μF isn't recommended as you may end up with values that are too small to be useful - ultimately this is a judgement call.

Log-taper pots are recommended - you'll have far more control over the attack/release values this way. 1M should give you a good range of values. Alpha pots are recommended since they'll afford a bit more support to the panel than just using the jacks alone.

### Files

* `dv3-schematic.png` - the schematic.
* `dv3-BOM.xlsx` - the BOM (Bill of Materials) file
* `dv3-panel.dxf` - the panel file in AutoCAD DXF format.
* `dv3-panel.fpd` - the panel file in Schaeffer FPD format. If you want to customise the panel then use this file and re-export it as a DXF or SVG file.