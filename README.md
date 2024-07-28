# Home Automation
 This project demonstrates how to create a home automation system using an ESP8266 microcontroller, the Blynk app, and a 4-channel relay. The setup allows you to control four different devices through the Blynk app on your smartphone.

 ## Components Required
 * ESP8266 (NodeMCU)
 * 4-Channel Relay Module
 * Connecting Wires
 * Power Supply
 * Wi-fi Network

 ## Circuit Diagram
 * D0 -> IN1
 * D1 -> IN2
 * D2 -> IN3
 * D3 -> IN4
 * GND -> GND
 * VIN -> VCC

 ## Blynk Setup
 * Download the Blynk app from the App Store or Google Play.
 * Create a new account or log in if you already have one.
 * Create a new project and select "ESP8266" as the device.
 * You will receive an authentication token via email. Replace the placeholder in the code with this token.
 * Add four buttons in the Blynk app interface and link them to Virtual Pins V0, V1, V2, and V3 respectively.
 * Set the buttons to switch mode.

 ## Installing Blynk Library
  To use Blynk with your Arduino IDE, you need to install the Blynk library:
  * Open the Arduino IDE.
  * Go to Sketch > Include Library > Manage Libraries.
  * In the Library Manager, type "Blynk" in the search bar.
  * Find "Blynk by Volodymyr Shymanskyy" and click the Install button.

Make sure you also have the ESP8266 board package installed. You can add the ESP8266 board to the Arduino IDE by following these steps:
* Open the Arduino IDE.
* Go to File > Preferences.
* In the "Additional Boards Manager URLs" field, add this URL: http://arduino.esp8266.com/stable/package_esp8266com_index.json.
* Go to Tools > Board > Boards Manager.
* Search for "esp8266" and install the latest version of the "esp8266" by ESP8266 Community.

## How to Use
* Power on your ESP8266.
* Open the Blynk app and connect to your project.
* Use the buttons in the Blynk app to control the relays. Each button corresponds to a relay channel, allowing you to turn connected devices on or off.

## Troubleshooting
* Ensure your Wi-Fi credentials and Blynk auth token are correctly entered in the code.
* Check all connections and ensure the relay module is powered.
* Make sure the Blynk app is connected to the same network as the ESP8266.

