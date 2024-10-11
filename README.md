
# Klipper Macros
| Macro |Description |
|--|--|
|PROBE_DEPLOY|As named.|
|PROBE_DOCK|Return to docked position & reset 'leaveprobe' to 0.|
|PROBE_CALIBRATE|As named.|
|PROBE_ACCURACY|As named.|
|START_PRINT|Preheats with BED_TEMP and EXTRUDER_TEMP as set in G-Code file from slicer.|
|END_PRINT|Cooldown sequence followed by conditional printer power off (END_POWER_SETTING)|
|PURGE_LINES|2 parallel lines from Y-max to 0 along the left side of the bed.|
|BED_MESH_CALIBRATE|Sets leaveprobe=1 for G28, if needed.  Includes adaptive=1.|
|G29|Calls BED_MESH_CALIBRATE|
|SCREWS_TILT_CALCULATE|Sets leaveprobe=1 for G28, if needed.|
|POWER_ON_PRINTER|As named.|
|POWER_OFF_PRINTER|As named.|
|END_POWER_SETTING|Select whether the printer powers down when finished.  Defaults to powering down.|
| SAVE_CONFIG |As named.|
|_VARIABLES|Macro to hold G-Code variables.|
|GET_VARIABLES|Search function to look up variables from the command line.|

# Klipper Menu
**MAIN (_main)**
 - Z Offset
 - Level Bed Screws

**PRINTING (_sdcard)**
 - Pause
 - Resume
 - Cancel
 
**MOVEMENT (_movement)**
- Steppers off
- Home All
 - Home Z
 - Home X/Y  
 - Move X:000 (1mm increments)
 - Move Y:000 (1mm increments)
 - Move Z:000 (1mm increments)
 - Move E:000 (1mm increments)
 
**TEMPERATURE (_temperature)**
 - Extruder:000 (0000)
 - Bed:000 (0000)

**SOFTWARE (_software)**
 - Save config
 - Restart host
 - Restart FW
 
**E-Stop**
## License
