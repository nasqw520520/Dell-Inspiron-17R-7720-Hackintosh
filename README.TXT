Dell 17R 7720 Hackintosh OpenCore EFI  
1.works with 10.15.7 
2. WIFI card was replaced with BCM94352
3.AppleALC layoutid is 2
4.Everything works except card reader
5.HDMI output should to be patched
AppleIntelFramebufferCapri.kext\Contents\MacOS\AppleIntelFramebufferCapri
open with UltraEdit replace (version depended)
04 00 66 01 01 03 01 01 00 00 00 02 00 00 00 01 00 00 00 60 10 07 00 00 10 07 00 00 00 00 00 00 90 EA 04 00 00 00 00 00 00 00 00 00 00 00 00 00 05 03 00 00 02 00 00 00 30 02 00 00 00 00 00 00 01 00 00 00 40 00 00 00 00 00 00 00 01 00 00 00 40 00 00 00 00 00 00 00 01 00 00 00 40 00 00 00
with (version indepent)
04 00 66 01 01 02 04 02 00 00 00 04 00 00 00 01 00 00 00 60 10 07 00 00 10 07 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 05 03 00 00 02 00 00 00 30 02 00 00 02 05 00 00 00 08 00 00 07 04 00 00 03 04 00 00 00 08 00 00 81 00 00 00 04 06 00 00 00 08 00 00 81 00 00 00  
then install this kext. Be aware of 10.15 permission change.
6.2K oupt support, install SwitchResX add 2K 54fps option.