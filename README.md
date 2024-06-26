# Automatic-Water-Dispenser-System
Designing and implementing a system that measures water flow and fills bottles with a predefined amount of water.

## Key Apparatus:
1. Arduino UNO
2. Water flow sensor
3. 4x4 keypad matrix
4. 5V Relay module
5. 5V DC water pump
6. 10uf polarised capacitor
7. 100uf polarised capacitor
8. 10k resistor
9. Jumper wires
10. MOSFET

## Block Diagram
![image](https://github.com/kmv19/Automatic-Water-Dispenser-System/assets/143374982/f76ae9f1-abfa-4167-a1c1-55caea85411e)

## Steps Involved
1. Connect a 4x4 keypad to the digital pins of an Arduino UNO and display the key presses on the serial monitor. The "D" key will function as "Enter," and the "*" key will function as "STOP."
2. Assemble a circuit on a breadboard that includes resistors, capacitors, and a MOSFET.
3. Connect the relay module, DC pump, and water flow sensor to the Arduino.
4. Attach the outlet of the DC pump to the inlet of the water flow sensor. The outlet of the water flow sensor will be used by the user to fill bottles.
5. By integrating all components, we will create an automatic water dispenser that allows the user to input the desired amount of water, which will then be dispensed automatically.

