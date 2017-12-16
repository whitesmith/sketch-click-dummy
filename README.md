# Clickable Prototype Sketch Plugin

Export HTML clickable prototypes directly from Sketch. Create links between screens by naming the layer link with `linkto:ArtboardName`.

# Installation
1. Download the files in this repository.
2. Open the `.sketchplugin` file.

# How to use
- To create a link to an Artboard, change the name of a layer to _linkto:ArtboardName_.
- Use _Export Clickable Prototype_ (^⇧⌘E) to export the HTML Clickable Prototype.
- Insert the dimensions of the main screen to clip scroll (or click ignore to skip clipping).
  Tip: the dimensions are auto-populated from the size of the first artboard (select Artboard > Send to back).

# Improvements
- [x] Export retina 2x images
- [x] Clip scroll (ideal for mobile prototypes)
- [ ] Add fixed elements (i.e.: bottom bar in mobile prototypes)

# Contributors
Tomás Marques <tomasmcm@whitesmith.co> (http://tomasmcm.design/)

Based of Frank Rausch's [Sketch Click Dummy](https://github.com/Raureif/sketch-click-dummy)

Uses the [Sketch Sandbox](https://github.com/bomberstudios/sketch-sandbox) library by Ale Muñoz.

# License
MIT License
