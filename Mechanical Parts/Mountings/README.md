# Mounting

In this folder you can find some parts used for assembling prototypes with 2020 profiles.

Check the images below to see if there is something of your interest.

Feel free to change it to your needs and share it with us. 😀

## Gantry plate

Gantry plate used as mounting place over a 2020 aluminum profile.

![Gantry_plate](Gantry_plate/Gantry_plate_20mm_v_slot.png)

## Generic 2020 profile extrusion

A simple generic 2020 V-slot Aluminium profile extrusion.

You can find more specific profile extrusions in the `Mechanical Parts/Profiles EN` folder.

![Aluminium extrusion](2020_V-slot_Al_extrusion/2020x50_V_slot_profile.png)

## Corner bracket

A simple corner bracket for joining 2020 profiles.

![2020 Corner bracket](Corner/2020_corner_bracket.png)

Also there is a file with multiple variants available in a `Configuration table`. In `Corner_bracket.FCStd` you will find the 20x20, 28x28, 30x30, 40x40, 58x58 models.

![Corner brackets, 5 variants](Corner/Corner_bracket.png)

## Linear Shaft Support

Precision stand up linear shaft support. Bore 8[mm].

### SK08, SKXX

Now with the 0.20 version is possible to use a `Configuration table`  to create multiple variants of the same model. In the `SKXX.FCStd` file you will find the SK08, SK10, SK12, SK13, SK16, SK20, SK25, SK30, SK35, SK40, SK50, SK60 models (configurations). Learn more about the [Configuration tables here](https://wiki.freecadweb.org/Spreadsheet_Workbench#Configuration_tables). Also watch [this video](https://youtu.be/D0f7bkNGAOg) to learn how this model was made.

![SK08](SK08/SK08.png)

![SKXX](SK08/SKXX.png)

### SHF08

![SHF08](SHF08/SHF08.png)

## Joining plates

For joining 2020 profiles in 90 degrees with extra support

### T shape

![T5](Joining_plate/T_5_holes.png)

### L shape

![L5](Joining_plate/L_5_holes.png)

### Multiple variants

Inspired by [Customizable Plate Bracket for Aluminium Extrusion Profiles](https://www.thingiverse.com/thing:2503622) by mightynozzle I decided to make some `Configuration tables` with various models, 6 types per shape.

![Plate brackets](Joining_plate/Brackets.png)


## Bearings

These bearing are usually used in assemblies with 2020 profiles. You can find more specialized bearing in the `Mechanical Parts/Bearings` folder.

### LM8UU, LMXXXUU

Now with the 0.20 version is possible to use a `Configuration table`  to create multiple variants of the same model. In the `LMXXXUU.FCStd` file you will find the LM6UU, LM6LUU, LM8SUU, LM8UU, LM8LUU, LM10UU, LM10LUU, LM12LUU, LM13LUU, LM16LUU, LM20LUU, LM25LUU, LM30LUU, LM35LUU, LM40LUU, LM50LUU and LM60LUU models (configurations). Learn more about the [Configuration tables here](https://wiki.freecadweb.org/Spreadsheet_Workbench#Configuration_tables).

![LM8UU](LM8UU/LM8UU.png)

![LMXXXUU](LM8UU/LMXXXUU.png)

### SC8UU, SCXXXUU

Parametric design using a `Configuration table`  to create multiple variants of the same model. Read about [Configuration tables here](https://wiki.freecadweb.org/Spreadsheet_Workbench#Configuration_tables).

![SC8UU](SC8UU/SC8UU.png)

![SCXXXUU](SC8UU/SCXXXUU.png)

## Pillow blocks

These pillow blocks are usually used in assemblies with 2020 profiles.
The very-detailed bearing model is a courtesy of [Jimmi Henry](https://grabcad.com/jimmi.henry-1), check it out at [grabcad](https://grabcad.com/library/608-skate-board-bearing-1).

### KP08

![KP08](KP08/KP08.png)

### KFL08

![KFL08](KFL08/KFL08.png)


## Leadscrews

Some leadscrew related parts.

### Tr8x8 leadscrew

* Thread: Tr8x8
* Starts: 4
* Lead: 8mm

The first 8 of Tr8 means it is to indicate the *diameter* (8mm) and the second 8 means the *lead*.
8mm lead means when drive by a stepper driver in *Full Step mode*, it moves 8mm per revolution.

![T8_leadscrew](T8_leadscrew/T8_leadscrew_150mm.png)


### T8 housing bracket

![T8_housing_bracket](T8_housing_bracket/T8_housing_bracket.png)


### Nuts

#### Tr8x8 flange nut

**IMPORTANT! Don't open this file in FreeCAD Link Branch from realthunder because of [this bug](https://github.com/realthunder/FreeCAD_assembly3/issues/1120).**

![Flange_nut](T8_screw_nut/Flange_nut/T8_Flange_nut.png)

#### Tr8x8 anti backlash nut

**IMPORTANT! Don't open this file in FreeCAD Link Branch from realthunder because of [this bug](https://github.com/realthunder/FreeCAD_assembly3/issues/1120).**

![Anti_backlash_nut](T8_screw_nut/Anti_backlash_nut/T8_antibacklash_nut.png)

Don´t forget to share your modifications with the community.

## T-slot nut

In the `T_type_square_nut.FCStd` file you will find the 20S-M3, 20S-M4, 20S-M5, 20S-M6, 30S-M4, 30S-M5, 30S-M6, 30S-M8, 40S-M4, 40S-M5, 40S-M6, 40S-M8, 45S-M4, 45S-M5, 45S-M6, 45S-M8 and 45S-M10 models (configurations). Learn more about the [Configuration tables here](https://wiki.freecadweb.org/Spreadsheet_Workbench#Configuration_tables).

This T-nut and other are now available in the [Fasteners WB](https://www.freecadweb.org/wiki/Fasteners_Workbench).

![Slot T square nut](Slot_T_nuts/T_type_square_nut.png)
