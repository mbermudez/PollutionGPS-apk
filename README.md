# PollutionGPS Android App #

Collects data from the NodeMCU ESP8266 CPU/WLAN sensor with SDS011 (fine dust sensor) and BME280 (temperature, humidity, and pressure) from [sensor.community](https://sensor.community/es/sensors/airrohr/). It stores the sensor data along with the Android GPS latitude and longitude in a CSV file within a folder inside the "Downloads" folder on Android.

Beware that the brisk movements of the sensor can cause false readings. Try to move the sensor gently. The app should always be on, so I added a wakeLock, which could drain the battery quickly. As the sensors need power, it is advisable to use an external battery to connect both the sensor and the cellphone.

You need to share the cellphone data connection with the sensor and configure the sensor to send the data to the HTTP service on the Android on port 8080. The app shows the IP address of the Android.


<p align="center">
<img src="./images/015.png" width="200">
</p>
More instructions soon...

This app was developed to provide independent measures of air pollution in Granada, thanks to the NGO [Andalucia Acción en Red](https://www.accionenred-andalucia.org/).
<p align="right">
<img src="./images/logo.png" width="50">
</p>

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
