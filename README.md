# 555-Timer-PWM-Sponsored-by-JLCPCB

Thank you JLCPCB for sponsoring this project. Please order your PCBs at https://jlcpcb.com/RAT

Hardware components
JLCPCB Customized PCB ×	1

NE555 Timer through hole ×	1	

IC socket 8 pins 2.54mm through hole ×	1	

Male Header 40 Position 1 Row (0.1") ×	1	

1N4007 – High Voltage, High Current Rated Diode ×	2	

3386 100k Ohm Potentiometer ×	1	

0.25W 10k Ohm Resistor ×	1	

Capacitor 10 nF ×	2

Hand tools and fabrication machines

Soldering iron (generic)

Solder Wire, Lead Free

This project is about 555 Timer which produces varying duty cycle from about 36% to about 95% at fixed frequency. Use a ceramic capacitor for C2.

I would also like to thank the online community for sharing the schematic to build the circuit.

Why do we want a 555 Timer instead of a microcontroller signal output?

A 555 Timer can provide up to about 14V output peak to peak signal. Whereas, a microcontroller usually can provide up to 5V peak to peak signal.

Please use a constant input voltage of between 5V and 15V for the NE555 Timer.

For example, using the Frequency meter Arduino code, with R1 = 1 k Ohms, C1 = 33 nF.

With the help of an Arduino, you can use the Frequency meter .ino code to find out the frequency and duty cycle of a 555 Timer.

At lowest frequency, frequency = 14 kHz, duty cycle = 36%.

![image](https://user-images.githubusercontent.com/85741357/181508371-565dc27b-57df-4cbd-bbeb-10ea0fd26b5a.png)

Lowest frequency

At highest frequency, frequency = 16.6 kHz, duty cycle = 95%.

![image](https://user-images.githubusercontent.com/85741357/181508468-058eb018-774d-4378-907d-b588b6c69e45.png)

Highest frequency

I have yet to figure out the formula for calculating the frequency of the 555 Timer for this setup. Do let me know if you have the answer.

One application of sweeping duty cycle 555 Timer is the use in varying the voltage of a motor, thus in turn varying the speed of the motor.

Tips: JLCPCB offers cheaper price for small PCBs of 10cm by 10cm. You can panelize your PCBs to less than or equal to the dimension.

Hope you enjoy this project. Once again, I would like to thank JLCPCB for sponsoring this project, and please order your PCBs at https://jlcpcb.com/RAT
