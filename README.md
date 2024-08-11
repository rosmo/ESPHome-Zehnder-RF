# ESPHome-Zehnder-RF

This one is configured for an ESP32-C6 (nanoESP32-C6). Updated to use latest ESP-IDF. May not work
out of box since it uses latest Git.

1) Change board ID in utility-bridge.yaml
2) Set your GPIO pins there as well
3) Create secrets.yaml with:
```
esphome_utility_bridge_api_password: <password>
esphome_utility_bridge_ota_password: <password>
esphome_utility_bridge_ap_password: <password>
wifi_ssid: <wifi name>
wifi_password: <wifi password>
# Change these too:
wifi_ip_utility_bridge: 192.168.1.238
wifi_gateway: 192.168.1.1
wifi_subnet: 255.255.248.0
```