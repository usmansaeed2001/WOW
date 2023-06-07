<<<<<<< HEAD
# GPS Data Parsing Library
This library parses GPS Data in NMEA format to extract Latitude, Longitude and Time information from the data.
It also verifies the checksum of the data.
### Example NMEA Strings:
Here are some example strings that can be used to test this code:
#### Checksum Correct:
"$GPGGA,062153.00,3723.4658762,N,12158.1134279,W,2,08,1.2,21.0,M,-25.4,M,0000,0000*65"
"$GPGGA,164045.00,5351.1234,N,00215.6789,W,1,07,1.0,0.5,M,47.9,M,,*75"
Passing these strings will result in correct output, as the checksum is correct.
#### Checksum Invalid:
"$GPGGA,062153.00,3723.4658762,N,12158.1134279,W,2,08,1.2,21.0,M,-25.4,M,0000,0000*5E"
"$GPGGA,164045.00,5351.1234,N,00215.6789,W,1,07,1.0,0.5,M,47.9,M,,*62"
These strings do not pass checksum so the parsing_gps_function will output a false indicating that the checksum cannot be verified.
=======
ESP-IDF template app
====================

This is a template application to be used with [Espressif IoT Development Framework](https://github.com/espressif/esp-idf).

Please check [ESP-IDF docs](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html) for getting started instructions.

*Code in this repository is in the Public Domain (or CC0 licensed, at your option.)
Unless required by applicable law or agreed to in writing, this
software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.*
>>>>>>> 1619670 (Build FIles Added)
