
## ESP32-Cam Setup
**1:** Download Arduino IDE if you haven't already                  
**2:** Connect the Cam like so

If you're using FTDI:

![Wiring](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20191252.png)

If you're using TTL:

![Esp32](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20190541.png)

To

![TTL](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20190558.png)

**3:** Open Arduino IDE and go to files > prefrences > additional boards manager URLs

![prefrences](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20192352.png)

![URLs](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20192654.png)

**4:** put this into the box:
https://arduino.esp8266.com/stable/package_esp8266com_index.json
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
and press ok

**5:** go to Tools > Board > Boards manager

![boards manager](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20193100.png)

**6:** search esp32 and click install

![Install](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20193612.png)

**7:** go to boards > esp32 > AI Thinker esp32 Cam

![7th step](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20194040.png)

**8:** Connect your TTL or FTDI to your computer
**9:** go to file > examples > ESP32 > camera > camerawebserver

![8th step](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20194911.png)

**10** enter your Wi-Fi credentials here

![9th step](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20195329.png)

**10:** click the serial monitor button and set the baud rate to 115200

![Serial Monitor](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20203724.png)

**11:** press upload

![Uploading](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20203922.png)

**12:** Disconnect after Uploading

![Disconnect](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20191211.png)

**12:** Copy the IP Address

![Copy This](file:///C:/Users/Araab/OneDrive/Pictures/Screenshots/Screenshot%202024-07-23%20204555.png)

**13:** paste it into the browser and the control the camera from there!