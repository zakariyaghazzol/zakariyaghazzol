# Zakariya Ghazzol

Aerospace engineering undergraduate at the University of Central Florida, focused on avionics, embedded software, telemetry, and engineering verification.

## Engineering projects

### [Model Rocket Flight Computer](https://github.com/zakariyaghazzol/model-rocket-flight-computer)

C++17 flight-computer prototype with sensor filtering, flight-state classification, telemetry, fault detection, and synthetic-flight tests. Includes Python packet parsing and replay tools. Observation and logging only; hardware integration is in progress and the system has not flown.

### [LoRa GPS Telemetry and Ground Station](https://github.com/zakariyaghazzol/lora-gps-ground-station)

Arduino GPS transmitter and LoRa receiver with a Python ground station for GPS-fix monitoring, RSSI, packet-loss tracking, and CSV logging. A local bench run logged 20,152 packets over 5.7 hours with 0.55% reported packet loss. Public examples use synthetic positions rather than recorded location data.

### [ESP32-S3 Camera Recorder](https://github.com/zakariyaghazzol/esp32s3-camera-recorder)

Camera and microSD recording work on the XIAO ESP32S3 Sense, with Python tools for checking recorded clips. An earlier CameraWebServer-based setup saved 50 of 50 JPEG frames at 5 FPS over 10 seconds; the standalone recorder has compile and host-test verification. Extended recording and flight validation remain unfinished.

### [Solar Atlas - Stellarium Catalog Pipeline](https://github.com/zakariyaghazzol/solar-atlas-stellarium-pipeline)

Streaming Node.js binary-data converter and validator for a star-catalog rendering pipeline. Converted 586,525 records across four catalogs and reduced output size by 33.3%. Includes a recorded run manifest and synthetic end-to-end tests.

## Tools

C++17, Python, JavaScript/Node.js, Arduino, Git, CMake, and KiCad schematics and board placement.
