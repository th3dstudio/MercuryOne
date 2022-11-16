# Total BOM

### Main hardware components
- 2x motors
- 3x rails
- 1x gantry extrusion, 2020
- Belt (5m, cut-to-length during installation)
- 2x microswitch (or use sensorless homing if desired/available)

### Idler and pulley components:
- 10x dowel pins
- 20x shims
- 20x bearing halves
- 2x toothed pulley for motor shaft
- 2x toothed idler bearing

### M3 hardware:
- 8x M3 heat set inserts
- 22x M3 T-nuts (spring-lock or standard)
- 30x M3x8mm screws
- 8x M3x20mm screws
- 6x M3x30mm screws

### M5 hardware:
- 16x M5 T-nuts (spring-lock or standard)
- 2x M5x10mm screws
- 8x M5x12mm screws
- 2x M5x20mm screws
- 4x M5x50mm screws

# Printed Components

https://github.com/th3dstudio/MercuryOne/tree/main/M1.1%20Base%20Files

Print one of each of the following:

- FlangeSpacer_short_1.stl
- FlangeSpacer_short_2.stl
- FlangeSpacer_tall_1.stl
- FlangeSpacer_tall_2.stl
- XJoint_left_bottom.stl
- XJoint_left_top.stl
- XJoint_right_bottom.stl
- XJoint_right_top.stl
- Z_DropBracket_5Pro_1.stl
- Z_DropBracket_5Pro_2.stl
- front_tension_plate_t-nut_1.stl
- front_tension_plate_t-nut_2.stl
- front_tower_left.stl
- front_tower_right.stl
- stepper_mount_bottom_left.stl
- stepper_mount_bottom_right.stl
- stepper_mount_top_left.stl
- stepper_mount_top_right.stl
- tIdlerSpacer_short_1.stl
- tIdlerSpacer_short_2.stl
- tIdlerSpacer_tall_1.stl
- tIdlerSpacer_tall_2.stl

One of each file is fine. Note that the ones marked "1" and "2" are identical to each other, but are arranged this way so it's easy to track and make sure you have all of the pieces.

This means you can either use the 1 and 2 for clarity, or print two of either file for instancing.

# BOM Breakdown By Component

## Mechanics:
- 2x motors
- 3x rails
- 1x gantry extrusion 2020
- Belt
- 2x microswitches

## Stepper towers:
- 4x dowel pins
- 12x shims
- 12x bearing halves
- 6x M3x20 to attach motors to towers
- 2x toothed pulley for motor shaft
- 4x M5x50 to attach towers to frame
- 4x M5 T-nuts

## Tensioners:
- 2x heat set (front)
- 2x dowel pin
- 4x bearing halves
- 4x shims
- 4x M3x8 to attach plates to frame (or tap and use 1x screw)
- 4x M3 T-nuts to attach plates to frame (or tap and use 1x screw)
- 2x M5 T-nut to attach tensioner to frame
- 2x M5x20 to attach and lock tensioner to frame
- 2x M3x20 for belt tension adjustment (between tensioner plate and tensioner tower)

## X joints:

- 6x heat sets (undersides)
- 4x dowel pins
- 2x toothed bearing pulley
- 4x shims
- 4x bearing halves
- 6x M3x30 for attaching X joint halves together
- 8x M3x8 to attach assembled joints to rail carriages
- 8x M5 T-nuts to hold extrusion in place
- 8x M5x12 to hold extrusion in place

## Rails:
- 18x M3 T-nuts (6x per rail, 3x rails total)
- 18x M3x8 (6x per rail, 3x rails total)

## Y Endstop:
- 2x M5x10mm screws to attach housing to frame
- 2x M5 T-nuts to attach housing to frame

# This BOM Does not include...

- Belt clamps or hot-end carriage assembly (meaning this BOM alone cannot complete the motion system)
- Wiring extensions and/or electronics enclosure relocation (Fabreeko kit includes some wiring)
- X endstop trigger plate screws
