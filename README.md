# Customizable Graduation Keyring

A graduation-themed keyring with editable raised lettering and colour controls, designed for OpenSCAD and MakerWorld's Parametric Model Maker.

## Features

- Customize the name, font, size, spacing, position, rotation, width, and raised height.
- Choose colours for the base, artwork, and name.
- Match the face, nameplate background, and lower panel to the base, use one shared colour, or colour them individually.
- Self-contained SCAD file—no external STL or libraries required.

## Files

| File | Purpose |
| --- | --- |
| [Keyring_Exact_Outlines_Inset_Colours.scad](Keyring_Exact_Outlines_Inset_Colours.scad) | Customizable model |
| [Prints/SampleWithAMSPrinter.3mf](Prints/SampleWithAMSPrinter.3mf) | Two-colour AMS example |
| [Prints/SampleWithLayerPause.3mf](Prints/SampleWithLayerPause.3mf) | Manual filament-swap example |

## Customize and print

1. Open the SCAD in OpenSCAD or MakerWorld's Parametric Model Maker.
2. Adjust the lettering and colours, then render or generate the model.
3. Export/download the model and open it in Bambu Studio.
4. Check text fit, place the model on the bed, assign filaments, and inspect the sliced preview.
5. For printing without an AMS, add and verify a pause at the desired colour-change layer.

The supplied print profiles use PLA, a 0.4 mm nozzle, 0.2 mm layers, 2 walls, and 15% infill, with supports disabled.

## Limitations

- The supplied 3MF profiles contain a fixed example name; customization does not update them.
- The SCAD does not add print pauses or start a print automatically.
- Long names or placement adjustments can extend beyond the nameplate. Check the preview before printing.
- Verify colours and filament assignments in Bambu Studio; STL exports do not retain colours.
