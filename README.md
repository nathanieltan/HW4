# CompArch HW b0100 Submission: Register File #

I hope you enjoy my verilog.

## Deliverable 1:
![Good Register Implimentation](https://github.com/nathanieltan/HW4/blob/master/regGood.jpg)
![Bad Register Implimentation](https://github.com/nathanieltan/HW4/blob/master/regBad.jpg)

## Deliverable 6:
The decoder works by bit shifting enable by the address. If enable is a 1, the 1 will be bit shifted so that the one aligns with the register that is supposed to be enabled, and all other registers will recieve a 0. If the enable is a 0, all of the registers will recieve a 0. This thus decodes the address for the registers.
