# EnergyPro-Energy-Theft-Detection-System
EnergyPro — Energy Theft Detection System
<img width="720" height="402" alt="WhatsApp Image 2026-05-06 at 00 22 18" src="https://github.com/user-attachments/assets/b4e2647a-c6ba-41bc-a1e5-b71c9cfa199c" />


An IoT-based smart energy monitoring system that detects unauthorized electricity usage in real time — combining embedded hardware with a live web dashboard for anomaly detection and power control.


📌 Project Overview
EnergyPro is an academic embedded systems project that monitors electricity consumption, detects anomalies indicative of energy theft, and provides remote power control via a web interface. It tracks voltage, current, and power in real time and triggers alerts when usage patterns deviate from expected thresholds.

🖼️ Dashboard Screenshots
Energy Dashboard — Real-Time Monitoring
<img width="720" height="402" alt="WhatsApp Image 2026-05-06 at 00 22 18" src="https://github.com/user-attachments/assets/156a410d-c47b-46b4-97e5-4bef353ac6d5" />

Power Control Panel
<img width="720" height="421" alt="WhatsApp Image 2026-05-06 at 00 22 19 (1)" src="https://github.com/user-attachments/assets/93909164-8ae8-4f7c-a13a-e19eb0755d82" />

Account Management
<img width="720" height="400" alt="WhatsApp Image 2026-05-06 at 00 22 18 (1)" src="https://github.com/user-attachments/assets/d57e584b-96ef-485d-a8cb-1f179c0d64db" />

System Settings
<img width="720" height="409" alt="WhatsApp Image 2026-05-06 at 00 22 19" src="https://github.com/user-attachments/assets/626ec566-7fd3-4ca7-8ddc-e4d4d916a8cf" />


📊 Live Metrics Tracked
MetricExample ValueAvailable Credit₹ 100.00Line Voltage243.0 VLine Current0.105 AActive Power15.1 WTotal Energy Consumed49,285.170 kWhTheft Detection✅ Active

⚙️ System Features

Real-Time Monitoring — Live voltage, current, and power readings from hardware sensors
Theft Detection — Configurable threshold-based anomaly detection flags suspicious usage
Power Control — Manual ON/OFF relay control + Auto mode based on balance and safety
Account Management — Prepaid credit system with recharge functionality
Safety Thresholds — Configurable over-voltage (250V) and over-current (8A) limits
Security Settings — Adjustable theft detection sensitivity threshold
Fault Status — Automatic disconnection on fault detection


🛠️ Tech Stack
ComponentTechnologyHardwareEmbedded microcontroller (ESP/Arduino), Current & Voltage sensorsBackendPython / Node.js (local server)FrontendWeb dashboard (HTML/CSS/JS) — EnergyPro UICommunicationLocal network (IP: 172.20.81.198)Data AnalysisCurrent flow anomaly detection via threshold logic

🔍 How Theft Detection Works

Sensors measure real-time current flow from the electricity line
Readings are compared against a configurable theft threshold
If consumption pattern deviates unexpectedly (e.g., bypass detected), the system:

Flags a theft alert on the dashboard
Can automatically cut power via relay if Auto Control is enabled


All events are logged in the Reports section


📁 File Structure
energy-theft-detection/
│
├── hardware/
│   └── circuit_diagram.png             # Wiring and sensor setup
├── firmware/
│   └── main.ino                        # Microcontroller code
├── dashboard/
│   └── app.py                          # Web server / backend
├── screenshots/
│   ├── energy_dashboard.png
│   ├── power_control.png
│   ├── account_management.png
│   └── system_settings.png
└── README.md

🚀 Setup & Run
bash# Install dependencies
pip install flask

# Run the web server
python dashboard/app.py




Swasti Parashar
B.Tech Electronics & Telecommunication | Bharati Vidyapeeth College of Engineering, Pune
📧 swastiparashar522861@gmail.com
🔗 GitHub
