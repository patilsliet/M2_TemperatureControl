# TempratureControl


### Theory

The temperature control system is used to control the temperature of the car seat. If the user or driver of the vehicle resides in the vehicle, a button sensor is activated. After that, the user gets access to turn on the heater. The temperature sensor keeps track of the temperature and sends an analog value to the small controller. The microcontroller analyzes the analog input of the temperature sensor and removes the temperature by serial communication. All control system functions are performed on a microcontroller called Atmega328.

The circuit operates by monitoring the temperature from the external input and comparing the temperature with the set temperature. The output power of the circuit is disconnected or switched off or the alarm goes off when the input temperature is equal to or greater than the set temperature value. The method of operation involves the use of precise line sensors, that is, they produce a voltage directly proportional to the temperature. Basically the system is built using temperature sensors and compressors. The system is powered by 12V power supply. Test results show that the circuit output is off which is why the SWITCH off device or alarm is ON when the device exceeds the set temperature. The normal operation of the system and operation depends on the temperature difference between the set temperature range and the outside temperature intended for monitoring. The whole system was tested and found to be fully functional.
