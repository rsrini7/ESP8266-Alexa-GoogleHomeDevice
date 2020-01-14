# NodeMCU Alexa & Google Home Device

All libraries included

Use a NodeMCU (ESP-12E) to control literally Anything in your house by turning into a Smart Switch.

### STEP 0 - What you will Need:
 1. NodeMCU
 2. Micro USB Cable
 3. Arduino IDE

### STEP 1:

1. Register for an account (https://sinric.com)
2. Login and create a smart home device (Dashboard -> Add smart home device)
3. Copy your API Key from dashboard
4. Change the Arduino Sketch. Replace the API Key, Wifi SSID and Password
5. Change the Device ID in Arduino Code to that supplied on Sinric Dashboard
6. Install Amazon Alexa Smart Home Skill and Link to your Sinric account. https://www.amazon.com/dp/B078RGYWQQ
7. Google Home setup mobile : https://github.com/kakopappa/sinric/wiki/How-to-use-Google-Home
 
### STEP 2: Connecting NodeMCU to Arduino IDE

1. Download or Clone Repository
2. Open Arduino.IDE 
    Add http://arduino.esp8266.com/stable/package_esp8266com_index.json into the “Additional Boards Manager URLs
    Board Manager > search ESP8266 and install
3. Copy the Libraries to Arduino libraries folder
4. Connect led in D2 NodeMCU
5. Restart IDE
5. Open the sketch needed (NodeMCU_Alexa_GoogleHome.ino)
6. Select Generic ESP8266 and port
6. Upload
7. Test in your mobile with Alexa App and Google Assistance.
