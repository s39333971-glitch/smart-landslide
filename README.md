# Smart Landslide Monitoring & Early Warning System 🏔️[span_2](start_span)[span_2](end_span)

A comprehensive, real-time geotechnical monitoring and early warning dashboard designed to track slope displacement, hydrological conditions, and landslide risk indices for vulnerable hilly terrain[span_3](start_span)[span_3](end_span).

---

## 🚀 Key Features

* **Real-Time Displacement & Tilt Tracking:** Continuous 60-minute trend monitoring using MPU6000 inclinometer fusion filters[span_4](start_span)[span_4](end_span).
* **Hydrological & Rainfall Monitoring:** Tracks cumulative rainfall intensity ($12.5\text{ mm/h}$) and pore pressure metrics[span_5](start_span)[span_5](end_span).
* **Landslide Risk Index (LRI):** Dynamic risk calculation gauge ($12 / 100$) providing immediate threat assessment[span_6](start_span)[span_6](end_span).
* **Emergency Warning Controls:** Interactive command panel to trigger emergency drain pumps, sound field alarm sirens, and simulate slope emergency scenarios[span_7](start_span)[span_7](end_span).
* **Telemetry & Audit Logging:** Live system logs tracking telemetry status, sensor re-calibrations, and automated actuator actions[span_8](start_span)[span_8](end_span).
* **Multi-Language Support:** Integrated language toggle options (e.g., English / Local Language support)[span_9](start_span)[span_9](end_span).

---

## 📊 System Overview

* **Active Node:** NODE #OAK3-HILL-04[span_10](start_span)[span_10](end_span)
* **Power Source:** Solar + LiFePO4[span_11](start_span)[span_11](end_span)
* **Telemetry Interval:** $90\text{s}$[span_12](start_span)[span_12](end_span)
* **Alert Broadcast:** Transmitted via LoRa gateway and encrypted MQTT protocol to District Disaster Management Cell[span_13](start_span)[span_13](end_span).

---

## 💻 Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript
* **Icons & UI Elements:** FontAwesome / Custom Dashboard Components
* **Hardware Integration (Simulated/Supported):** MPU6000 Inclinometer, LoRa Gateway, MQTT Protocol
