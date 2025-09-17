#Automated Watering System
What This Project Does?
This project is an automated watering system for plants. It uses a soil moisture sensor connected to an Arduino to check how wet the soil is. When the soil gets too dry, it turns on a water pump to water the plant automatically.

Components;
*Arduino Uno
*Soil moisture sensor
*Relay module (to control the pump)
*Water pump (or an LED for testing)

How It Works?
The moisture sensor sends data to the Arduino. If the soil moisture is below a certain level (which you can adjust), the Arduino switches the relay on, which powers the water pump. When the soil is wet enough, the pump turns off.

How to Use;
*Connect the components as shown in the wiring diagram (I can share one if needed).
*Upload the Arduino code to the board.
*Adjust the moisture threshold if needed to fit your soil type.
*The system will water the plant whenever the soil is dry.

What I Learned?
This project helped me understand how to connect sensors with a microcontroller and control devices using a relay. It also taught me about reading analog sensor data and writing simple control logic in Arduino.

Possible Improvements?
Adding a Wi-Fi module to control or monitor the system remotely.
Using weather data to water plants more smartly.
Creating a mobile app to check the soil moisture status.
