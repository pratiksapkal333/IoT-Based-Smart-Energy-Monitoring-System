⚡ IoT-Based Smart Energy Meter using ESP32

An IoT-based smart energy monitoring system that measures real-time voltage, current, and power consumption, and displays the data locally on an LCD as well as remotely via the Blynk cloud platform.

📌 Overview

This project uses an ESP32 microcontroller along with voltage and current sensors to monitor electrical parameters in real time. The system sends data to the cloud for remote monitoring and also displays it on an LCD for local viewing.

It is designed for:

Home energy monitoring
Load analysis
Basic smart grid applications
IoT learning projects
🚀 Features
📡 Real-time monitoring via WiFi
⚡ Voltage measurement using ZMPT101B
🔌 Current measurement using ACS712
📊 Power calculation (Voltage × Current)
📱 Remote monitoring using Blynk app
🖥️ LCD display for live values
💾 Expandable for data logging & automation
🧰 Components Used
ESP32 Development Board
ZMPT101B Voltage Sensor
ACS712 Current Sensor
16x2 LCD Display
Resistors, Wires, Breadboard
Power Supply

⚙️ Working Principle
The ZMPT101B sensor measures AC voltage and outputs an analog signal.
The ACS712 sensor measures current flowing through the load.
ESP32 reads analog signals using ADC.
Voltage and current values are processed and calibrated in code.
Power is calculated using:
Power=Voltage×Current
Data is:
Displayed on LCD
Sent to Blynk cloud via WiFi

⚠️ Limitations
Requires calibration for accurate readings
Not suitable for high-precision industrial use
Sensitive to noise in analog signals

🔮 Future Improvements
Energy consumption tracking (kWh)
Data logging to cloud/database
Mobile alerts for high usage
Relay control for automation
Web dashboard (instead of only Blynk)

🧠 Learning Outcomes
ESP32 & IoT integration
Sensor interfacing
ADC signal processing
Cloud communication
Embedded system design

📜 License

This project is open-source and available under the MIT License.

🙌 Acknowledgment

Inspired by IoT-based smart energy monitoring systems and practical embedded learning projects.
