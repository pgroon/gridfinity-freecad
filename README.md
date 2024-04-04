Description

Automatically generate Gridfinity templates of any size in FreeCAD, the free and open source parametric modelling software available to anyone at no cost. Check www.freecad.org.

The models correctly implement all features included in the official gridfinity specification:

    0.25mm offset between baseplate and bins
    Stackable lip on the top rim of the bins, also with correct offset
    Holes for magnets
    Holes for M3 screws

31.03.2024: VERSION TWO IMPROVEMENTS!
Due to the amazing feedback and suggestions I received in reply to version one, I thoroughly updated the model to add many new features.

    Wall-thickness is now a variable parameter.
    label-tab/handles are now an option, either full width or specified length.
    Zack's original bottom-scoop to easier extract tiny parts is also implemented.
    None of these require messing with the model. All features are now fully controlled from the spreadsheet.
    Added many, many more annotations and explanations to the spreadsheet for those who want to learn how to do similar stuff in FreeCAD. 
    The screw holes received the advanced printability treatment (sequential bridging) to avoid micro-spaghetti in the holes.
    For the stacking profile at the top, I implemented an improved version (which I will duly credit here as soon as I find that damn link again). It removes the second, lower chamfer of the stacking profile. Strictly speaking this is a very slight deviation from “official” gridfinity spec - But it saves material and improves print time with literally no downsides while maintaining full compatibility with Zack's original design, so I saw no reason not to use it.

Also noteworthy:

    Beginner-friendly - All features are named, the spreadsheet is annotated, so it's easy to understand for everyone. I'm happy to answer questions too, so if you're new to FreeCAD and need help, feel free to reach out!
    Solid bins for cutting into, or hollow bins for filling out!

I took great care to model all these features independently of each other to create the most stable possible model. 

Everything is created in official branch FreeCAD version 0.21.2

TODO: 
 - Divider vanes to create bins with subcompartments.
How to use

Open the model in Freecad. Double click the “data” entry in the feature tree to open the spreadsheet. Adjust values to your hearts content, and watch the model update in real time. 
Pro tip: Click on the “Windows” menu, then select “tile” to view both the model view and the spreadsheet in split-screen-mode.
Making adjustments

All changes to the base model values should be made via the spreadsheet. Don't change stuff in the sketches themselves, or it will no longer update correctly. If you open a sketch and see a constraint in an orange font rather than the normal red, that means it's a calculated value based on the spreadsheet. Be careful not to break the formulas unless you know what you're doing.

Happy gridding!
