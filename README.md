# Simple Camera Web Server Stock Example with ESP32 Lilygo T-Camera

This sketch is an updated and edited version of the 'official' ESP32 Camera example sketch, tailored to work seamlessly with the ESP32 Lilygo T-Camera. The modifications primarily focus on updating the camera pin numbers in the configuration to ensure compatibility and proper functioning with the ESP32 Lilygo T-Camera.


## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/filippoberti2020/esp32-camera-web-server.git
    ```

2. Configure the necessary settings in the code.

3. Upload the code to your ESP32 Lilygo T-Camera.

4. Power on the camera and access the webpage using the local ip of the device.

## Configuration

- Update the relevant settings in the `config.h` file:

```cpp
#define WIFI_SSID "YourWiFiSSID"
#define WIFI_PASSWORD "YourWiFiPassword"
```

## Contributing

If you'd like to contribute or have suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
