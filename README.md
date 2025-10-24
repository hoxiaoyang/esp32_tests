# esp32_tests

1. `sound_test`: connect MakePython ESP32 with KY-037 sound sensor. Outputs analog and digital values on display every 200ms

A0: connected to GPIO 35 (ADC1 pin), shouldn't conflict with WiFi which might cause the I2C synchronization error?

D0: connected to GPIO 19

VCC: connected to 3.3V

G: connected to GND