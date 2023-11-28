# ZX-Interface-1-Recreated
Sinclair ZX Interface 1 recreated with Sinclair Routing

This is Kicad 7 project of the Sinclair ZX Interface 1 that uses the same routing and PCB size as the orignal.
A raw board was scanned and the top and bottom side images were imported into Kicad. This gave the board outline 
along with the position of components and the track layout.
The schematic available from the Service Guide was then redrawn in Kicad and used to recreate the PCB and to verify that the routing was correct.
The Bill of Materials from the Service Guide was used to select suitable footprints. Some parts could not be located and so suitable repalcements were used.

This is the result of that exercise.

The files 'Interface 1 Recreated with images.*' when combined will produce an Interface 1 Recreated.kicad_pcb file that includes the top/bottom images.
It appears that a 75MB is too be for uploading so I split it into 20MB chunks.

Sometimes Kicad complains that there is an issue with the edge.cuts file. Running DRC will show what it doesn't like and it's easy to fix so that the board outline is a closed shape.


