This adds the ability to change the WiFi connection settings using the SDCARD and a config.txt file. Make sure your sd card is formatted FAT32.

SSID=YOUR_SSID
PASS=YOUR_PASSWORD

In the config.txt enter your desired SSID and Password. After first upload insert the sd card with your config.txt file and reset the ESP32. It will load your wifi settings and store them in the EEPROM. If no SDCARD is present with new settings, then the EEPROM values will be use.

Other than SD Card WiFi settings updating, the original master code is the same minus any changes since I modified it.
