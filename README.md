# IoT-based-Smart-Irrigation-System-using-Soil-Moisture-Sensor-and-ESP8266-NodeMCU
Most of the farmers use large portions of farming land and it becomes very difficult to reach and track each corner of large lands. Sometime there is a possibility of uneven water sprinkles. This result in the bad quality crops which further leads to financial losses. In this scenario the Smart Irrigation System using Latest IoT technology is helpful and leads to ease of farming. \
 \
The Smart irrigation System has wide scope to automate the complete irrigation system. Here we are building a IoT based Irrigation System using ESP8266 NodeMCU Module and DHT11 Sensor. It will not only automatically irrigate the water based on the moisture level in the soil but also send the Data to ThingSpeak Server to keep track of the land condition. The System will consist a water pump which will be used to sprinkle water on the land depending upon the land environmental condition such as Moisture, Temperature and Humidity. \
 \
We previously build similar Automatic Plant Irrigation System which sends alerts on mobile but not on IoT cloud. Apart from this, Rain alarm and soil moisture detector circuit can also be helpful in building Smart Irrigation system. \
 \
Before starting, it is important to note that the different crops require different Soil Moisture, Temperature and Humidity Condition. So in this tutorial we are using such a crop which will require a soil moisture of about 50-55%. So when the soil loses its moisture to less than 50% then Motor pump will turn on automatically to sprinkle the water and it will continue to sprinkle the water until the moisture goes upto 55% and after that the pump will be turned off. The sensor data will be sent to ThingSpeak Server in defined interval of time so that it can be monitored from anywhere in the world. \

# Components Required
NodeMCU ESP8266 \
Soil Moisture Sensor Module \
Water Pump Module \
Relay Module \
DHT11
