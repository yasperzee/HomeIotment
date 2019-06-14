# Homeiotment
Building SmartHome using OpenSource software tools and affordable Hardware like NodeMcu and Raspberry pi
New version, no repos here, just documentation and instructions

Phase 1:
ESP8266 NodeMCU (ESP01 / ESP12E) as mqtt publisher with BMP180 sensor
c++, IDE is  ATOM w/ platformio project
UBUNTU laptop as Eclipse PAHO mqtt client
Related repos w/ source codes:
  - ESP12E paho_mqtt_client:  
      https://github.com/yasperzee/esp12e.git
  - mqtt_gsheet_gateway, Docker compliant Python3 app:   
      https://github.com/yasperzee/Python3.git
  - mosquitto server, Raspberry Pi3 image build with YoctoProject 2.6:
      https://github.com/yasperzee/Raspberry_PI3.git
  
Phase 2:
- ESP32 (SOC is xtensa lx6 by Tensilica)
  -https://ip.cadence.com/news/104/330/Tensilica-s-Xtensa-LX-Processor-Beats-All-Other-32-and-64-bit-Processor-Cores-On-EEMBC-Consumer-Out-of-the-Box-Benchmar
- FreeRTOS or NuttX RTOS
 
  
