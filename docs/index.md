---
menu: Welcome
weight: 0 # smaller weights rise to the top of the menu
---

### For [HealthyPi v3 Click here](http://healthypi3.protocentral.com/)

## Welcome to HealthyPi v4

HealthyPi 4 sets a new standard in open source health solutions with mobility, wireless and wearable capabilities. It enables the continuous real-time monitoring of human physiological data, which provides a snapshot of the user's medical condition within his/her environment and also medical research possibilities. It is comfortable to wear and does not restrict the user's freedom of movement and can also act as a battery powered standalone device.

![HealthyPi Display](images/HealthyPi_Complete.jpg)

HealthyPi v4 measures the following parameters in real-time and with high accuracy:

* Electrocardiogram (ECG) data, heart rate, and heart-rate variability
* Respiration based on Impedance Pneumography
* Pulse oximetry (SPO₂)
* Body temperature

HealthyPi 4 is affordable and accessible and the open source aspect means that it’s easy to expand on.
You can now purchase a HealthyPi v4 from [Crowd Supply](https://www.crowdsupply.com/protocentral/healthypi-v4-unplugged)

### Features
**Microcontroller and wireless connectivity:**  ESP32, in WROOM32 module format, with Dual-core Xtensa 32-bit CPU, 4 MB of on-board flash, Wi-Fi, and support for BLE

**Wireless interface:**  Wi-Fi and Access Point (AP) modes, a 2.4 GHz radio with an on-board PCB antenna that is compatible with Bluetooth 4.2 and BLE

**Firmware programming:** Supports Arduino IDE as well as Espressif ESP-IDF

**Sensors:**
ECG and respiration front end: Texas Instruments (TI) ADS1292R 24-bit analog front end with signal-to-noise ratio (SNR) of 107 dB
Pulse oximetry front end: TI AFE4400 pulse oximetry front end with integrated LED driver and 22-bit ADC

**Temperature sensor:** Maxim MAX30208 digital body temperature sensor for monitoring skin temperature

**Form factor:** Raspberry Pi HAT form factor (65 mm X 56 mm)

### Ports and interfaces:

* **On / Off Switch :** Powering the HealthyPi v4
* **USB-CDC :** On-board USB-TO-UART converter
* **2x Sparkfun QWIIC :** Compatible I2C ports for interfacing any wiic based sensors
* **Sliding switch :** Transition between two different modes(Pi3 mode and wearable mode)
* **On-board 3 LED :** Charge indication, BLE indication,Webserver indication
* **Push-button :** Switching between Communication Protocols(BLE and Webserver)

### Multiple operating modes, no programming required

#### * Wearable mode

![Wearable mode](images/wearable_mode.jpg)

The device communicates to android app via BLE. The real time vital signs (heart rate, respiration rate, spo2 and body temperature, histogram, heart rate variability) along with device battery level can be monitored  from the Android mobile application. Additionally, you can also view live streaming of ECG. Added on-board power source (Battery) enhances the device to be used in a complete wearable platform.

#### * Standalone webserver mode (IOT)

![Webserver Standalone](images/webserver_standalone.png)

Unlocking the possibilities of HealthyPi v4 as IOT, data can be displayed on the PC screen using a TCP communication. Connecting your smart devices with the “Healthypi_v4 ” in Wi-Fi Access Point (AP) can stream vital signs through webserver. The HealthyPi v4 webserver page displays live monitoring of physiological data. Additionally with added on OTA updates feature, you can easily update the firmware in minutes.

#### * Raspberry Pi "HAT" mode (HealthyPi v3 compatible)

![Pi3 mode](images/Pi3_mode.png)

Using the Raspberry Pi as its computing and display platform, The HealthyPi v4 add-on HAT turns the Raspberry Pi into a vital sign monitoring system.On successful interfacing of GUI with HealthyPi v4, ECG, respiration, spo2  waveforms and  its values along with temperature can be  streamed live through Raspberry Pi display or Computer monitor depending on the users choice. The user can also record the data for research and analysis.
