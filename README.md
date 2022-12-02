# 3D Printing Notes

## Useful Klipper codes
[G-Codes list](https://www.klipper3d.org/G-Codes.html)

* Home
```
G28 X0 Y0 Z0
```
* Baby step up
```
SET_GCODE_OFFSET Z=0.02 MOVE=1
```
* Set extrude factor override percentage
```
M221 S92
```
* ABL
```
BED_MESH_CALIBRATE
```
* MBL
```
BED_SCREWS_ADJUST
```

## Links
* [KLipper3D](https://www.klipper3d.org/)
