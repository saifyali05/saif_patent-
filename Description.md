The Smart Energy Meter is an IoT-based system that measures and displays
Voltage, Current, Power, Energy, and Power Factor of a connected appliance in real time.

It allows users to monitor electricity usage remotely using a web or mobile dashboard and helps in reducing power wastage and improving energy efficiency.

This system is part of a Patent Published innovation in the Indian Patent Office Journal No. 49/2025 (05-12-2025).

🧩 System Components
Hardware

ESP32 / ESP8266 Microcontroller

ZMPT101B Voltage Sensor

ACS712 Current Sensor

Relay Module (for load control)

AC Socket

Power Supply

Connecting wires

Software

Arduino IDE

Blynk IoT Platform

Required Libraries:

Blynk

ZMPT101B

ACS712

WiFi

ArduinoJson (optional)

📦 Required Libraries

Before uploading the code, install these libraries in Arduino IDE:

Blynk Library

ZMPT101B Voltage Sensor Library

ACS712 Current Sensor Library

How to Install:

Open Arduino IDE

Go to Tools → Manage Libraries

Search and install:

Blynk

ZMPT101B

ACS712

⚡ Sensor Working
ZMPT101B (Voltage Sensor)

Measures AC voltage of the appliance

Provides safe low-voltage analog output to ESP32

ACS712 (Current Sensor)

Measures current drawn by the load

Outputs an analog signal proportional to current

Using these values, the system calculates
Energy=Power×Time
🔌 How to Connect
Component	ESP32 Pin
ZMPT101B Output	Analog Pin
ACS712 Output	Analog Pin
Relay IN	Digital Pin
VCC	5V
GND	GND

⚠️ AC connections must be done carefully with proper insulation.

📲 Using the System
Step 1: Power the device

Connect the Smart Energy Meter to power and plug the appliance into the AC socket.

Step 2: Open the Blynk App

Login to the Blynk app and open the project dashboard.

You will see:

Voltage

Current

Power

Energy

ON / OFF Control

Step 3: Monitor Usage

The readings update in real time.
You can track how much electricity your appliance is consuming.

Step 4: Control the Load

Use the ON/OFF button to remotely control the appliance using the relay.

📊 Features

✔ Real-time voltage & current monitoring
✔ Power and energy calculation
✔ Remote access using Blynk
✔ Over-load detection (optional)
✔ Mobile & Web Dashboard
✔ Supports single appliance monitoring

🧠 Applications

Home energy monitoring

Hostel & PG electricity tracking

Smart plug

Appliance energy audit

IoT-based smart homes

🔐 Patent Information

This Smart Energy Meter system is a Patent Published Innovation:

Patent Office Journal: No. 49 / 2025

Publication Date: 05 December 2025

Country: India

The design and working of this system is a legally recognized technical invention.