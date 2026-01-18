# M5-Wrist-AirMouse-
A wearable Bluetooth LE HID mouse using M5StickC Plus 2. Features IMU-based tilt control for hands-free navigation on Android and PC. Inspired by Iron Man

This project transforms an M5StickC Plus 2 into a wrist-mounted wireless mouse using Bluetooth Low Energy (BLE). Originally inspired by the HUD and gesture-based tech from Iron Man, this device allows for complete hands-free cursor control on Android, PC, and iPad.

Designed with a cost-efficient DIY approach, it proves that high-end wearable tech doesn't have to be expensive. Whether it's for playing Minecraft with a new level of immersion or navigating a mobile phone without touching the screen, this project bridges the gap between hardware and intuitive user experience."

Key Engineering Highlights:

IMU-Driven Logic: Uses the BMI270 6-axis IMU to map wrist tilt (Pitch/Roll) to mouse cursor movement.

Custom UX Calibration: Integrated custom sensitivity and deadzone logic to ensure precision and reduce wrist fatigue (Static Muscle Strain).

Cross-Platform Compatibility: Operates as a standard HID device, requiring no extra apps on the host device.

Open-Source & Scalable: Built on ESP32-BLE-Mouse library with a focus on low-latency performance.
