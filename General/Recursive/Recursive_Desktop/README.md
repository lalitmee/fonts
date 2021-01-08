# Installation recommendations

It is possible to install both static & variable fonts without font menu conflicts, as these are given distinct font family names.

However, it is useful to install only the specific static fonts you need from this folder or you may experience conflicts in use.

## General Desktop use (Word, PowerPoint, Keynote, InDesign, Illustrator, PhotoShop, etc)

- On Windows, install `Recursive_Desktop/recursive-statics.ttc` (This is a collection of all 64 static instances in TTF format) *OR* the separate TTFs from the `separate_statics` folder (better for the design app Figma, as well as for older systems).
- On Mac, install `Recursive_Desktop/recursive-statics.otc` (This is a collection of all 64 static instances in OTF format) *OR* the separate OTFs from the `separate_statics` folder (better for the design app Figma, as well as for older systems).

## Desktop web design (Sketch) & experimental use in Adobe apps

- Install `Recursive_Desktop/Recursive_VF_1.0XX.ttf` (this is the full Recursive variable font)
- It may also be beneficial to install static fonts, as OS & app support of variable fonts is still growing

**NOTE: Currently, variable fonts do not export to PDFs cleanly from Adobe apps.** This is something Adobe is working on, and it is not an issue in Recursive. So, if you are designing for print, it is recommended that you use static OTFs rather than variable fonts. If you do use variable fonts in print design, be sure to check the output PDFs to ensure that styles are not mixed in unexpected ways (e.g. letters within the same words may have inconsistent weights, etc).
