# IOT
Cloud platform git repo 


Understanding MQTT - Ubuntu 
MQTT

https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-the-mosquitto-mqtt-messaging-broker-on-ubuntu-16-04

sudo apt-get install mosquitto mosquitto-clients
mosquitto_sub -h localhost -t test
mosquitto_pub -h localhost -t test -m "hello world"


Docker on Raspberry Pi
https://medium.com/@tukai.anirban/docker-on-raspberry-pi-getting-started-c7b403205ecf

https://www.loraserver.io/guides/debian-ubuntu/#setting-up-your-first-device

https://www.loraserver.io/guides/first-gateway-device/


Using MQTT to access AWS IOT cloud links:
	https://docs.aws.amazon.com/iot/latest/developerguide/iot-sdks.html#iot-python-sdk
	https://github.com/aws/aws-iot-device-sdk-python
	https://github.com/aws/aws-iot-device-sdk-python/blob/master/README.rst


Using MQTT to access Azure IOT cloud links:
	https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-mqtt-support
	https://github.com/Azure/azure-iot-sdks
	https://github.com/Azure/azure-iot-sdk-python


LORA for Raspberry Pi
	https://www.loraserver.io/lora-gateway-os/overview/
	https://www.loraserver.io/lora-gateway-os/install/raspberrypi/

LORA Gateway Hat for Raspberry Pi:   
https://uk.pi-supply.com/products/iot-lora-gateway-hat-for-raspberry-pi



IOT Device connection through open source AZURE IOT CENTRAL:

https://azure.microsoft.com/en-us/blog/connect-devices-from-other-iot-clouds-to-azure-iot-central/

Git Repo: https://github.com/Azure/iotc-device-bridge


Tutorial to add device:

https://docs.microsoft.com/en-us/azure/iot-central/tutorial-add-device



Server Authentication details:

https://docs.aws.amazon.com/iot/latest/developerguide/managing-device-certs.html#server-authentication


Steps for AWS setup:

https://circuitdigest.com/tutorial/getting-started-with-amazon-aws-for-iot-projects


**PROJECT DESCRIPTION**

Industry 4.0 and smart industrial automation requires data anaysis of the manufacturing shop floor. Sensors at the plant throw out a lot of information which can be collected and analysed using data analysis techniques used in controls and data science. Using this data studies, two major things are acomplished. Firstly, optimization of current processes minimizing wastage and increasing overall efficiency. Secondly, an implementation of a connected enterprise is created which supports collaboration of intelligent devices to achieve specialised tasks.

**CONNECTING SENSOR DEVICE TO IOT**

The sensors present can be used for gathering information on the plant floor. Packets of data in the form of CayenneLPP are sent to IOT network device which in turn provides a gateway to the payload to be sent onto the internet through WiFi. 

Current Setup of the industry standard sensors included LORAWAN server to send the data to the ThingsNetwork saving the encoded packet of data.

The new setup for the sensors use MachineQ gateway to receive data from the wireless sensors within a distance of 3kms. The maximum distance of the sensors is yet to be tested for the prefect transmission of data.

Packets of data from the MachineQ are sent onto the internet by connecting the MachineQ gateway to the internet router. Current gateway is registered to the company which ensures no unauthorised access of the device. 
	
Packets of data are then sent to Microsoft Azure IOT Hub cloud service which can be used as the one point access for collcting the data for analytics.

Task of analysing the data and applying models will then proceed once all data is in pre processed form.

**SETTING UP MICROSOFT AZURE TO RECEIVE SENSOR DATA**

**SETUP OF UBUNTU VIRTUAL MACHINE ON AZURE**

**DATA VISUALIZATION AND DOCKER SETUP**

**MODEL ESTIMATION**









MQTT - Uses publisher subscriber model for information exchange.