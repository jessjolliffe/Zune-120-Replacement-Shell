# Zune 120 Replacement Shell

This design is currently in its very early days. There are several known design issues still present. This modification requires careful assembly and should not be attempted unless you really know what you're doing. I've run this with my 120 for a while now, without any issues - but I can't promise reliability or that I haven't overlooked something.

<img width="1080" height="1920" alt="image" src="https://github.com/user-attachments/assets/812f7cf7-2c25-489e-a6c1-0c9d1859e092" />

---

# Required Parts:

* **14x** M1.2-0.25 x 3mm screws
* **14x** M1.2 x 2mm L x 2mm OD heat inserts
* **1x** M85K USB-C adapter board (available on AliExpress & other suppliers)

---

# Printing:

This shell has been tested using SLA/resin 3D printing from JLC3DP.

* 8001 Resin
* Transparent finish with the Oil Sprayed surface treatment.

This design may be printable with other manufacturers and with other settings, but these are the only settings I've directly checked. The main issue will be finding a process that provides a transparent enough part for the "screen" part of the design.

---

# CNC:

Initially the intention was to have the parts machined from Polycarbonate for the faceplate, and aluminium for the rear plate. The design is currently not ready for CNC manufacture as there are a number of flagged issues when submitting to PCBWay and JLCCNC. It was also quite expensive, so I don't really want to "test it" until I'm more sure on the design.

---

# Known Issues:

There's still a bunch of stuff I need to fix with this, here are some that I know about - but I'm sure there are many more to find.

### 1. Screen Clarity

Because the front screen cover is 3D printed resin, it is usable and clear enough to read the display, but it does lack clarity and the experience is slightly "smeary" when you look at it closely.

### 2. Warping on the Front Plate

The front screen section is designed to be very thin in order to ensure the orioginal buttons feel similar to the original part. Because it's so thin, it makes the part quite susceptible to warping during the print and curing process which can cause issues with the final print and some of the button housings to break or snap.

If you do get it printed, I recommend ordering 2 or 3 front pieces at a time so you can pick the one with the best result without having further delays. 

### 3. Squircle Pad Clearance

Also related to issue 2, the front face has a tendency to curve away slightly from the top of the Zune's directional squircle pad. This can interfere with the physical "down" click of the pad as it really needs the D-Pad to be pushed flush up against the front face to click properly.

You can carefully bend the front plate back into the correct shape or press down with your finger just above the D-Pad at the same time you click down on the D-Pad, which will help. You can use the swipe function of the touch pad fine so I'd recommend that right now until it's fixed.

Future revisions of this design will likely include extra bracing or thickened walls to address this mechanically. I just haven't quite figured this out yet.

### 4. USB-C Charging Speeds

Currently, my test unit does not charge at the full speed of the original connector. It's very slow. I've had some issues with both the PCB and battery which could be related, so I'm still looking into this. I just haven't been able to confirm properly if this slow charging rate is due to the M85K component, issues with my PCB, issues with my soldering, or something else entirely new.

### 5. "Hold Switch"

Currently the designed hold switch replacement part is too small to be printed by JLC3DP, and does not properly fit inside the slot. It can be used, but it's awkward. I would recommend either skipping putting the hold switch in, or just making sure that it's switched to "unlocked" for the time being until I (or someone else!) can design a replacement switch/switch housing.

### 6. No Original Connector Access

My original goal for this project was a complete, easy to print replacement shell - in order to get my design to accomplish this I needed to cover the original connector. The walls of the printed part are much thicker than the original shell which means the data cable has to go a lot further into the housing. I had some issues with designing a slot that can accomodate the chunky original connector housing, and as I was intending to move to USB-C anyway I didn't spend too much time trying to come up with a solution.
