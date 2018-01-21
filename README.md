# Kicad footprint and library of AM3352 ZCE 298 bga
BXL file of the footprint was downloaded from Ti website.
BXL file was transformed using UltraLibrarian to kicad format.
The kicad format exported by UltraLibrarian has bugs so it does not open in Kicad Nightly. It opened in kicad 4.6, however the pins seemed messed up.  
The lib file was hand edited to make it compatible with kicad nightly.

BXL -> Eagle (shows correct number of pads in eagle) -> Kicad (shows 312 pads) conversion also looses functional aggregation of pads.
BXL -> Kicad with functional aggregation or sequential aggregation results in different number of balls. Must be a bug.
BXL -> Kicad sequential contains same number of pads as that of BXL-> Eagle -> Kicad. I am using this version to edit and create the lib.

