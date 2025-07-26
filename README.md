# iot-smart-home-automation
This project presents the design and implementation of a Smart Home 
Automation System with Remote Access, enabling users to control household 
appliances such as bulbs and fans using a mobile application through Blynk. 
The core of the system is built around the NodeMCU (ESP8266) 
microcontroller, which connects to the internet and facilitates communication 
between sensors and actuators. 
The system integrates various sensors including the DHT11 temperature and 
humidity sensor, LDR (Light Dependent Resistor) for ambient light detection, 
and IR sensors for object detection. Additionally, a relay module is used to 
control high-voltage appliances like lights and fans. The system supports both 
manual control (through the Blynk app) and automatic control, where 
appliances respond to sensor inputs — for example, turning on the fan if the 
temperature exceeds a certain threshold, or switching off lights based on 
ambient light detected by the LDR. 
This smart automation not only enhances user convenience and comfort, but 
also contributes to energy efficiency and home security. Real-time data 
monitoring and control from anywhere make the system scalable and practical 
for modern home environments.

**Libraries Used:**
ESP8266WiFi.h → For Wi-Fi connection.
BlynkSimpleEsp8266.h → For Blynk IoT platform integration.
