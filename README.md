To flash the c6
1. build the application in esp_serial_flasher/examples/esp32_example
2. solder jumper on the horizontal pads above the c6 module qr code
3. flash & wait

To alter c6 firmware
1. alter application in slave/ folder
2. Build application
3. Copy slave/build/network_adapter.bin to esp-serial-flasher/examples/binaries/ESP32_AT_Firmware/ESP32_C6
4. Follow steps on flashing the c6

Hello world contains the project that tries to enable the display
