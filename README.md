# ATRescueBoard
### Full credit for the original version to Jeff Keyzer [http://mightyohm.com](http://mightyohm.com)

Atmel "rescue" board for ATMega and ATTiny X4/X5: to recover fuses setting with High Voltage Programming. 

The PCB is a simplified Arduino shield, with sockets for ATMega and ATTiny; as 12V source the Vin Arduino 
pin has to be used, so the **Arduino must be powered externally with a 12V power supply!**

The micro code is uploaded to the ATmega328P on the Arduino, and comunicate with the user via the serial
interface. Three different mode can be selected:
* ATMEGA: mode for ATmega 128/168/328;
* TINY2313: not supported in this hardware version, look for original version at [https://mightyohm.com/blog/products/hv-rescue-shield-2-x/](https://mightyohm.com/blog/products/hv-rescue-shield-2-x/);
* HVSP: mode for ATtiny X4/X5;



