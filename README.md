# Indoor Smart Night Light

### Problem statement 
People often forget to turn off indoor lights during the day, which wastes electricity and money. Also, walking through pitch-black rooms at night is difficult and can cause people to trip or fall. This project solves these problems by building a smart system that manages itself without manual switches.

### Description 
An indoor smart light prototype built inside a model house. It watches the brightness of the room through the house openings, automatically turning the light ON when it gets dark and keeping it OFF during the day to save energy.

### Components required 
* **9V Battery:** Gives power to the circuit.
* **Photoresistor (LDR):** Senses the light levels in the room.
* **NPN Transistor:** Acts as an automatic electronic switch.
* **LED Light:** The indoor safety night light.
* **Piezo Buzzer:** Plays a short chime when night mode turns on.
* **Resistors:** Protect the parts from getting too much current.
* **Breadboard & Wires:** Used to connect all the parts together easily.

### Principle 
The circuit works on the rule of **light-controlled resistance**. When light shines on the photoresistor, its electrical resistance drops. When it gets dark, its resistance shoots up, which tells the transistor switch to turn ON.

### Working 
1. During the day, light enters the model house and hits the photoresistor, keeping its resistance low.
2. This low resistance keeps the transistor turned OFF, so the light stays deactivated.
3. At night, the room goes dark, causing the photoresistor's resistance to go very high.
4. This high resistance forces voltage into the transistor base, turning its **P-N junctions ON**.
5. The transistor completes the circuit loop, instantly turning the LED ON and sounding the buzzer chime.

### Notes
* **Add a timer:** Add a simple timer so the buzzer only chimes for one second instead of staying on all night.
* **Add a dial:** Add a potentiometer (dial resistor) to let you adjust exactly how dark the room needs to be before the light turns on.
* **Use real appliances:** Add a relay module so this low-power circuit can safely control a real, full-sized house light bulb.
* **Go solar:** Swap the 9V battery for a rechargeable battery and a small solar panel on the roof of the model house.
*
