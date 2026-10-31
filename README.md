# Velocity Deck
General Description: A small cool designed keyboard addition to the Macbook pro to do Onshape quickly and learn PCB design. 

     - able to do 2 types of modes 
         - one specifically for Onshape 
         - one for KiCad 
     - an in-between button to switch the two. 
    Total: 12 Cherry MX key switches + 2 rotary encoders. 

Why?: a Macropad with optimal traces + code to make it as a fast as possible at taking inputs + Able to switch between KiCAD and Onshape keybinds quickly/easily + Really cool Keyboard Case! 


Velocity Deck
Velocity Deck is a 4 key macropad with a rotary encoder, an OLED Display. It also has 2 WS2812B Leds, and uses QMK firmware

It serves as an example piece/reference for the hackpad YSWS, since it contains an implementation of every common part.

Features:
Currents music album by Tame Impala case inspiration. looks looks awesome doesn't it??
2 EC11 Rotary encoders for whatever you want
12 Keys

CAD Model:
Everything fits together using 4 M3 Bolts and heatset inserts. All around the edges. Its completely flat

It has 3 separate printed pieces. The top Currents cover, Middle piece that holds components together, and top piece to keep everything together/ hold the PCB.  




#BOM 
|Designator                                                                               |Footprint                                                           |Quantity|Value                                             |Price |
|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------|--------|--------------------------------------------------|------|
|D1, D10, D11, D12, D13, D14, D15, D16, D17, D18, D19, D2, D20, D3, D4, D5, D6, D7, D8, D9|D_DO-35_SOD27_P7.62mm_Horizontal                                    |20      |1N4148 (THT) Diode                                |$5    |
|S1, S10, S11, S12, S13, S14, S15, S16, S17, S18, S19, S2, S3, S4, S5, S6, S7, S8, S9     |MX_PCB_1.00u                                                        |19      |MX Switches                                       |$20   |
|SW1                                                                                      |RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm_CircularMountingHoles|1       |EC11 Rotary Encoder                               |$5    |
|U1                                                                                       |SOIC-28W_7.5x17.9mm_P1.27mm                                         |1       |MCP23017 Surface Mounted                          |$2    |
|U2                                                                                       |Seeed_XIAO_RP2040                                                   |1       |Seeed Xiao RP2040                                 |$7    |
|R1, R2                                                                                   |0603                                                                |2       |4.7 kΩ 0603 package 1/10 W surface-mount resistors|$3    |
|~                                                                                        |~                                                                   |1       |PCB                                               |$5    |
|~                                                                                        |~                                                                   |4       |4mm*2mm Circular Neodymium Magnets                |$10   |
|~                                                                                        |~                                                                   |4       |4mm*30mm Keyboard Gasket Strips                   |$7    |
|~                                                                                        |~                                                                   |4       |3D Printed Parts                                  |$10   |
|~                                                                                        |~                                                                   |4       |Macbook Pro Rubber Feet                           |$5    |
|~                                                                                        |~                                                                   |1       |Set of 2U PCB Mounted MX Stabilizers              |$10   |
|~                                                                                        |~                                                                   |15      |1U Keycaps                                        |varies|
|~                                                                                        |~                                                                   |1       |1.25U Keycaps                                     |varies|
|~                                                                                        |~                                                                   |2       |1.5U Keycaps                                      |varies|
|~                                                                                        |~                                                                   |1       |2U Keycap                                         |varies|
|~                                                                                        |~                                                                   |~       |~                                                 |Total $ 110-120
