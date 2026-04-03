# ✈️ Project AeroStack: Full-Scale Flight Ecosystem

A comprehensive embedded systems project integrating real-time flight control, telemetry bridging, and a modern web-based Ground Control Station (GCS).

---

## 🗺️ Project Roadmap

### Phase 1: Hardware & Avionics (The Physical Layer)
*Focus: Assembly, power distribution, and sensor calibration.*
- [ ] **Component Selection:** Finalize airframe, high-torque servos, and BLDC motors.
- [ ] **MCU Architecture:** Setup **Arduino** (Mega or Due) as the primary Flight Controller.
- [ ] **Sensor Fusion:** Interface MPU6050/BNO055 (IMU) for orientation and BMP280 for altitude.
- [ ] **Power Management:** Design a robust BEC (Battery Eliminator Circuit) system for 5V/12V rails.

### Phase 2: Firmware Development (The Brain - C++)
*Focus: Low-latency control loops and stabilization.*
- [ ] **PID Implementation:** Develop $C++$ logic for stabilization of Pitch, Roll, and Yaw.
- [ ] **Actuator Control:** Map PWM signals to ESCs and control surfaces.
- [ ] **State Machine:** Program flight modes (Manual, Stabilize, Autopilot, Failsafe).
- [ ] **Interrupt Handling:** Optimize sensor polling using hardware interrupts.

### Phase 3: Telemetry & Middleware (The Bridge - Python)
*Focus: Data transmission and protocol translation.*
- [ ] **Radio Link:** Establish long-range communication using LoRa or HC-12 modules.
- [ ] **Python Gateway:** Build a script to decode Serial data into structured JSON.
- [ ] **Data Stream:** Implement a WebSocket server to pipe live data to the frontend.
- [ ] **Blackbox Logging:** Local storage of flight telemetry for post-flight debriefing.



## Currently WORKIN ON PHASE 1, 
So, there's no file here, just the roadmap and myself
