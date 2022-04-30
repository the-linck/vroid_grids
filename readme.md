# VRoid Grids

SVG Recreations of the texture grids used for models in VRoid Studio, created with Inskcape. Every part used by VRoid when reading textures is filled with the grids on the right position, every part no used is simply empty.

All files were created in 1920px resolution, but being vectors should easily handle higher resolutions.
Some details that would fill lest than a pixel on this resolution were not included.

They can be improved with minor adjustments, though for most cases that improvements would be useless.

## Structure

The images area created atop of the full grids VRoid expects the user to import when dealing with models, so you can make your textures perfect without having to use it's integrated image editor.

Every file is divided into several layers, with layers for pre-built content (allows easily using colors, gradients or patterns), layers for grids (to create custom items aligned with VRoid grid) and groupping layers (to better focus on what you want to create/edit).

This files and folders compose this project:

* **svg**  
Folder with the original .svg files, the main part of this project.
    * Full Body.svg  
    Used for both skin textures and clothes that directly overlay the skin (like underwear).
    * **Tops**
        * T-Shirt.svg
        * Mini_T-Shirt.svg
* **previews**  
Folder with .png previews of all SVGs.

## Layers

Each layer can be (un)locked and show/hidden, no matter if it is on a group or not. Using this possibility is highly recomended when creating clothes that will fill only part of the editing area.

Along with groups to quickly show/hide parts, there's one convention followed on the project: grid layers go atop of content layers, to help on alignment.

### Full Body

* Head (group)  
Textures used to paint the back of the head.
    * Head-back Grid
    * Head Back
* Torso (group)  
    * Neck Grid
    * Waist Grid
    * Hip Grid
    * Torso Grid  
    Useful when you need to edit the whole torso at once
    * Hip
    * Waist
    * Neck
* Arms
    * Fingers Grid
    * Hand Nails Grid
    * Hands Grid
    * Arms Grid
    * Hand Nails Top
    * Hand Nails Bottom  
    Yep, you can paint the bottom part of the nails
    * Fingers
    * Hands
    * Wrists
    * Elbows
    * Shoulders
    * Arm Pits
* Legs
    * Toe Nails Grid
    * Foots Grid
    * Legs Grid
    * Toe Nails  Top
    * Toe Nails Bottom
    * Foots
    * Knees
* Background  
A bitmap screenshot of the VRoid body grid - used as a reference to create the grids.

### Tops

For this moment only layers for different grids are provided on tops.

## Exporting textures

You will need to export a bitmap version of the texture before using it on VRoid. Before doing this, remeber to make all grids an unused parts invisible, so you will used only what you do want.

Depending on the application the textures will serve, it might be a good idea to export several diffent sizes.