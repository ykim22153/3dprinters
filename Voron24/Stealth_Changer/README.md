# StealthChanger Upgrade of Voron 2.4 350 mm
### Original HW Configuration:
Voron 2.4 rev C LDO Kit  
BTT Kraken Mainboard  
CNC Part Kit
Voron Tap 2.0
Clicky-Klack Door


Hardware kits were purchased from various vendors including KB-3D.com, Fabreeko.com and West3D.com.

### Very useful websites for build and configuration instructions:  
LDO Documentation on StealthChanger: [https://docs.ldomotors.com/en/StealthChanger/planning_guide](URL)  
DraftShift Design Git Repo: [https://github.com/DraftShift](URL)  
AntHead Toolhead Git Repo: [https://github.com/PrintersForAnts/AntHead](URL)  
StealthChanger Documentation: [https://www.stealthchanger.com](URL)  
N3MI StealthChanger Guide for AntHead: [https://github.com/N3MI-DG/sc-guides/tree/main/Anthead](URL)  
Sdylewski's Documentation: [https://sdylewski.github.io/StealthChanger/](URL)  

## Hardware Parts and Kits:
1. StealthChanger Base Kit
2. StealthChanger Top Hat and Door Buffer Kit
3. StealthChanger Tool and Dock Kit
4. LDO Orbiter v2.5
5. OSS 2 Filament Sensor
6. Revo Hotend HF 60W

##Toolhead Selection and Modifications
N3MI magnetized Anthead

## Printed Parts BOM:
RED Parts are printed with eSun ABS+
BLUE Parts are printed with Creality ABS

### AntHead Tool Head:  
1. RED -- ant_head_main_body_voron_o2_hf_x1.stl
2. RED -- [a] Nozzle LED Carrier.stl
3. BLUE -- [a] Nozzle LED Restraint.stl
4. BLUE -- [a]_hex_gril_x1.stl
5. BLUE -- [a]_revo_voron_x1.stl
6. BLUE -- Left_Duct_Standard.stl (Magnetized)
7. BLUE -- Right_Duct_Standard.stl (Magnetized)

### Modular Frame
1. RED -- Top_Crossbar.stl
2. RED -- Bottom_Crossbar.stl
3. RED -- Left Standard.stl (Magnetized)
4. RED -- Right Standard.stl (Magnetized)
5. RED -- Pucks Standard.stl (Magnetized)

| SC Component       | Part Name                             | Part Color | Part URL                                                                                                                   |
| ------------------ | ------------------------------------- | ---------- | -------------------------------------------------------------------------------------------------------------------------- |
| AntHead Toolhead   | ant_head_main_body_voron_o2_hf_x1.stl | RED        | https://github.com/PrintersForAnts/AntHead/blob/main/STLs/Main_Bodies/O2/Voron/ant_head_main_body_voron_o2_hf_x1.stl       |
| AntHead Toolhead   | [a] Nozzle LED Carrier.stl            | RED        | https://github.com/PrintersForAnts/AntHead/blob/main/UserMods/SF_Nozzle_LEDs/STL/%5Ba%5D_Nozzle_LED_Carrier.stl            |
| AntHead Toolhead   | [a] Nozzle LED Restraint.stl          | RED        | https://github.com/PrintersForAnts/AntHead/blob/main/UserMods/SF_Nozzle_LEDs/STL/%5Ba%5D_Nozzle_LED_Restraint.stl          |
| AntHead Toolhead   | [a]_hex_gril_x1.stl                   | BLUE       | https://github.com/PrintersForAnts/AntHead/blob/main/STLs/Grills/%5Ba%5D_hex_grill_x1.stl                                  |
| AntHead Toolhead   | [a]_revo_voron_x1.stl                 | BLUE       | https://github.com/PrintersForAnts/AntHead/blob/main/STLs/Hotends/%5Ba%5D_revo_voron_x1.stl                                |
| AntHead Toolhead   | Left_Duct_Standard.stl                | BLUE       | https://github.com/DraftShift/ModularDock/blob/main/UserMods/N3MI-DG/Anthead%20Front%20Magnets/STL/Left_Duct_Standard.stl  |
| AntHead Toolhead   | Right_Duct_Standard.stl               | BLUE       | https://github.com/DraftShift/ModularDock/blob/main/UserMods/N3MI-DG/Anthead%20Front%20Magnets/STL/Right_Duct_Standard.stl |
| Toolhead Backplate | Anthead_HF.stl                        | RED        | https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Anthead_HF.stl                                      |
| Toolhead Spacer    | Anthead_Spacer_Full.stl               | RED        | https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Anthead_Spacer_Full.stl                             |
| SC Modular Frame   | Top_Crossbar.stl                      | RED        | https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/2020/Top_Crossbar.stl                                       |
| SC Modular Frame   | Bottom_Crossbar.stl                   | RED        | https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/2020/Bottom_Crossbar.stl                                    |
| SC Modular Frame   | Left Standard.stl (Magnetized)        | RED        | https://github.com/DraftShift/ModularDock/blob/main/UserMods/N3MI-DG/Anthead%20Front%20Magnets/STL/Left%20Standard.stl     |
| SC Modular Frame   | Right Standard.stl (Magnetized)       | RED        | https://github.com/DraftShift/ModularDock/blob/main/UserMods/N3MI-DG/Anthead%20Front%20Magnets/STL/Right%20Standard.stl    |
| SC Modular Frame   | Pucks Standard.stl (Magnetized)       | BLUE       | https://github.com/DraftShift/ModularDock/blob/main/UserMods/N3MI-DG/Anthead%20Front%20Magnets/STL/Pucks%20Standard.stl    |
| SC Modular Base    | Base.stl                              | RED        | https://github.com/DraftShift/ModularDock/blob/main/STLs/Anthead/Base.stl                                                  |
| SC Modular Base    | Back.stl                              | RED        | https://github.com/DraftShift/ModularDock/blob/main/STLs/Anthead/Back.stl                                                  |
| FannyPack          | [a]_sc_voron_cover.stl                | BLUE       | https://github.com/DraftShift/CableManagement/blob/main/STLs/FannyPack/STLs/%5Ba%5D_sc_voron_cover.stl                     |
| FannyPack          | base.stl                              | BLUE       | https://github.com/DraftShift/CableManagement/blob/main/STLs/FannyPack/STLs/base.stl                                       |
| FannyPack          | [a]_hexa_bracket_v1.3.stl             | BLUE       | https://github.com/DraftShift/CableManagement/blob/main/STLs/FannyPack/STLs/brackets/main/%5Ba%5D_hexa_bracket_v1.3.stl    |
| DoorBuffer         | Top left corner.stl                   | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Top%20left%20corner.stl           |
| DoorBuffer         | Top right corner.stl                  | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Top%20right%20corner.stl          |
| DoorBuffer         | Top.stl                               | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Top.stl                           |
| DoorBuffer         | Bottom left corner.stl                | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Bottom%20left%20corner.stl        |
| DoorBuffer         | Bottom right corner.stl               | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Bottom%20right%20corner.stl       |
| DoorBuffer         | Bottom.stl                            | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Bottom.stl                        |
| DoorBuffer         | Right.stl                             | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Right.stl                         |
| DoorBuffer         | Left.stl                              | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Clicky-Klack/Standard%20docks/350/Left.stl                          |
| DoorBuffer         | 2020_doorbuffer_adapter_x2.stl        | RED        | https://github.com/DraftShift/DoorBuffer/blob/main/STL/Adaptor/2020_doorbuffer_adapter_x2.stl                              |
| Top Hat Hinge      | LDO TopHat Hinge (3mm foam).stl       | RED        | https://github.com/MotorDynamicsLab/LDOStealthChanger/blob/master/STLs/LDO%20Tophat%20Hinge%20(3mm%20foam).stl             |



