# Group-410_Tomato_Detection
Optical sorting is used in various indus-
tries, where colour, size and shape can be
used to group the products. In this pro-
ject a prototype for proving the feasibil-
ity of an optical sorting system using color
threshold to detect and reject green toma-
toes was developed. The system is im-
plemented as an embedded system with a
line scan camera, three 8-bit ADCs, and an
FPGA development board. The system is
capable of running at 8.2 M pixels a second
which corresponds to the pixel density of
1.67 pixels
mm in the proposed setup. A UART
module was developed to act upon user
input and to log results while an external
screen was implemented to show the out-
put in the form of arms activated and the
intermediate results with the true and false
values from the threshold analysis. The
code is written in VHDL using Vivado
2022.2 and the FPGA development board
used is the CMOD A7 35T. Testing of the
prototype was done by having test images
roll down on a tv screen upon which the
line scan camera was positioned. Although
being bottlenecked by the limited bright-
ness of the tv screen, an accuracy of re-
spectively 100 % and 97 % was achieved.
