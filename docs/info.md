<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Switch 1 (IN0): Power switch
Switch 2 (IN1): Light changing sequence start switch
Switch 2 high: Red to green to yellow to red (loops with timed delay)

## How to test

LED1 (red) should be on indefinitely if IN0 (power switch) is high and IN1 (sequence switch) is low. If the sequence switch is on, the lights
loop from red to green to yellow to red and so forth. If the switch is turned off during the sequence, the sequence will finish before stopping
at red. If the power switch is off, none of the LEDs should be on.

## External hardware

Two switches provide inputs and three LEDs (red, yellow, green) are outputs.
