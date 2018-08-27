# Metro Mini Battery Shield

## Summary
The Metro Mini Battery shield was designed as part of an introductory PCB design course with the primary goal of being the primary power source and power platform for several other shields (I.E. physically identical "daugther" boards) that would plug into it. 

The battery shield was designed with the following requirements/features in mind:

-Be able to supply approximately 1A of continuous current in order to power Metro Mini and up to three other “daughter” boards
-Be able to charge an externally connected LiPo battery
-Be able to charge an externally connected LiPo battery and still power the Metro Mini and up to three other “daughter” boards all at the same time
-Be able to take power in from either an external source or from the USB cable connected to the Metro Mini board
-Be able to switch between USB power and battery power automatically in the case that either one is not available
-Be able to measure current draw using a built-in current sense resistor
-Be able to set the charge rate in order to select different charge rates based on different power inputs (USB, external ,etc)
-Feature an On/Off switch in order to disable the charger completely if necessary
-The fuel gauge needs to be able to report battery statistics to the Metro Mini over I2C at a regular interval such that the tri-color LED can be used as a visual indication of the “fuel” level of the battery
-Feature an built-in 5V step-up regulator that can take a wide range of input voltage and output a constant 5V (primarily used for stepping up LiPo 3.7V to 5V)


