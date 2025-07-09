# Box for dog treats with magnetic lid

Practical box intended for carrying dog treats with options for open and closed belt clip. The lid has embedded magnets for ease of use. Should be easily printed without supports, but requires pause during print to insert the magnets.

![Photo of dog treat box](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/Box01-small.jpg)

![Photo of dog treat box with lid opened](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/Box02-small.jpg)

The box features two options for belt clips. One of them is a conventional open clip which slides on and off your belt easily:

![CAD screenshot of open belt clip](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/BeltClipOpen-small.png)

The other clip attaches permanently to your belt, and is more suitable when doing various dog sports or other hefty physical activity:

![CAD screenshot of open belt clip](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/BeltClipClosed-small.png)

## How to print

None of the models require supports, so printing should be straight forward. Inserting the magnets will require some effort, though, see below.

The closed/permanent belt clip should be printed laying down, with 100% infill like this:

![Print orientation closed belt clip](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/PrintOrientationClipClosed-small.png)

The open belt clip should be printed on its side with generous brims, something like this:

![Print orientation closed belt clip](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/PrintOrientationClipOpen-small.png)

## Inserting magnets

The magnets are embedded into the print by pausing the print job. This is supported by most modern printers and slicers.

**IMPORTANT** Make sure to use some adhesive when inserting the magnets. In my case (using a more or less stock Ender 3), one of the magnets snapped on to the print head as it moved past the magnet. This might or might not be an issue on your printer.

 You can probably use some thin double sided tape, but **make sure the magnets do not protrude beyond the layer height**. If they do they will crash with the nozzle. Recommended method is a tiny bit of super glue and leave it for sufficient time to cure before resuming the print.

Pause the print before the first layer above the magnet compartment like this:

![Screenshot of slicer showing where to pause print](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/MagnetPauseBox-small.png)

Similar for the lid:

![Screenshot of slicer showing where to pause print](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/MagnetPauseLid-small.png)

## Assembly

The lid is fastened on a rod which goes through the hinges on the back. To secure the rod two screws are mounted on each side of the rod. There is also a printed washer to make it look a bit nicer:

![Lid assembly](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/LidAssembly.jpg)

The clips are fastened to threaded inserts inserts on the back side:

![Threaded inserts](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/Box04-small.jpg)

![Belt clip assembled](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/Box03-small.jpg)

**IMPORTANT** Do not use screws longer than 8mm, or they will screw through the inner wall of the box:

![Screenshot of slicer showing where to pause print](https://raw.githubusercontent.com/funkyfourier/dogtreatbox/refs/heads/master/release/v1/pics/ScrewLength-small.png)

## Bill of materials

* 2 20x10X2mm magnets
* 5 M2 screws, **max 8mm length**
* 5 M2 washers, max 5mm diameter
* 3 M2 threaded inserts, 3mm length

## Remixing

The box is modelled in [FreeCAD](https://www.freecad.org/). If you open the spreadsheet you will see various parameters you can tweak to your liking. Changing the parameters may blow up the model, but adjusting them within reason should work. For learning FreeCAD [MangoJelly Solutions for FreeCAD](https://www.youtube.com/channel/UCUWhaOxsRk_5oPPq00_Y7Dw) is highly recommended.

## Disclaimer/warning on bottom

There is a disclaimer/warning on the bottom of the box advicing not to throw it in the dishwasher and using it for dry treats only. These warnings largely depends on the filament and 3d printer, but for conventional 3d printing with PLA they probably apply. There are .3mf files with and without the warning, so you can decide wether to keep them or not.

## License

This work is licensed under a [Creative Commons (4.0 International License) Attribution-NonCommercial](https://creativecommons.org/licenses/by-nc/4.0/)