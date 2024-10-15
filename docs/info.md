<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is fairly straightforward as it is my first TT run and I know time is of the essence ... of which in this case there is a lot of but much waiting. This circuit is a binary counter using flip flops that can also be `crudely reset` by the dip switch attached. There is also a gate example on the GPIO pins that are included with TT09. The way to test this is to hook up a 1HZ oscillator (you could go faster but I would recommend a 1HZ freq) to the clk pin and to provide power to the processor then watch the output as the LEDs start counting up. These will go to 15 (hex F) and then roll back to 0 (so you could even say it goes to 30... a stretch). The figure below has the circuit I created. 
![image](https://github.com/user-attachments/assets/f1011d7f-737e-423b-a597-18efb5453d04)

## How to test

Explain how to use your project

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
