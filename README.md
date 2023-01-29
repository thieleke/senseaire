# senseaire
ESPHome configuration for a Senseair S8 LP / ATH20 sensor suite

A simple ESP32 powered temperature, humidity, and CO₂ sensor package, with OLED output (SSD1306 128x64), MQTT publishing of data in JSON format, web server for direct access, and NTP time support.

See the senseaire.yaml file for the default GPIO pin usage and/or modify as necessary.


# Example secrets.yaml file
ssid: MY_WIFI_NAME
wifi_password: hunter2
mqtt_server: 192.168.0.1
mqtt_username: senseair
mqtt_password: monkey123
ntp_server: pool.ntp.org
