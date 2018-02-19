This repository has files needed to create and adjust the template files for a
Dice Tower constructed of PVC pipe and fittings.

See https://github.com/oelgern/dice_tower/wiki for more information about the
dice tower project.

The dice tower template allows quick marking of drill holes. The resulting two
tabloid-sized pages are to be fastened to a 4" Schedule-40 PVC pipe. Markings on
template indicate the:
 Ends (length) of the pipe
 Pilot holes and full-sized holes for flat, lower baffle's support as well as
   standard baffles (all constructed from 1/2" PVC pipe).
 Dice exit gate

An additional template file for the lower baffle platform (made of paneling or
thin plywood) is also included.

This repository also contains the generated files for convenience.

Steps to create templates (if not modifying the templates skip to the step 4):

1. At bash shell: bc -l body_dimensions.bc > librecad_commands.txt
Output is commands that can be entered into LibreCAD's command window.

2. Paste the following set of commands from the commands file each into their
     own layer in LibreCAD using the Paste Multiple Commands function:
      Paper Outline
      Sheet 1
      Sheet 2
Note that the Paste Multiple Commands function is not available in the LibreCAD
version in the Ubuntu repository. It is available, however, in version
2.2.0-alpha.

3. Print PDFs from LibreCAD using the following options and functions in the
     following order for each sheet:
      File -> Print Preview
       Select a scale of 1:1 in the scale drop-down menu.
       Select the Center to page option.
      File -> Print
       Select Print to File (PDF) from the Name drop-down menu.
       Select Properties.
        Select Ledger / ANSI B from the Page size drop-down menu.
        Select Portrait (Ledger is landscape version of Tabloid, so this puts
          page into Landscape-esque mode).
        Select OK.
      Enter an appropriate name into the Output file field.
      Select Print.

4. Use your favorite PDF viewer to print the resulting PDF files without
     changing paper size or scaling.

5. Tape sheet 1--the bottom portion of the template that includes the dice exit
     gate--to the bottom portion of the 4" pipe. Butt the bottom edge of sheet 2
     against the top edge of sheet 1 and tape to the pipe. The 4" piece should
     now be ready for drilling and cutting.

6. Tape the baffle template to the paneling and use a sharp knife to cut through
     the template paper, scoring the paneling. This scoring can be marked with a
     pencil to provide a very visible line for cutting out the baffle.
