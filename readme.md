# M.2-Card-Footprints

![preview](preview.png)

The footprints were created in Eagle. The KiCad versions are imports, they are looking good but you might want to look for quirks.

The only footprint that has been verified with a PCB is the B-Key footprint though they all derive from the blank key footprint. So as long as the correct pads are removed the key is in the right place you should have no issues with other keys.

You can use the blank key footprint to create any other key like A or E Key A+E etc.

By default they are 2242 but if you want longer ones you just push the top outline including the half hole up to the dimension you want. So instead of having it sit are 42mm Y height you push it to 80mm if you want 2280.

M.2 Keying always uses the same pin names, you just delete some of the pad depending on which key is used and add the notch in that place.
You can find all the information you need about M.2 devices and their pinout in this M.2 Specs. You can find the doc on archive.org: https://web.archive.org/web/20200613074028/http://read.pudn.com/downloads794/doc/project/3133918/PCIe_M.2_Electromechanical_Spec_Rev1.0_Final_11012013_RS_Clean.pdf