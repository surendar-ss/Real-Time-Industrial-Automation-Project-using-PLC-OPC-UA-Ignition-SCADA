# Real-Time-Industrial-Automation-Project-using-PLC-OPC-UA-Ignition-SCADA

# Industrial Automation Project – PLC + OPC UA + SCADA

Overview
This project demonstrates a real-time industrial automation system using PLC programming, OPC UA communication, and SCADA visualization.

The system monitors water level and controls a motor automatically using logic implemented in the PLC.

 Technologies Used
PLC Programming (CODESYS)
OPC UA Server & Client
Ignition SCADA
Industrial Communication

## ⚙️ System Functionality
Monitors water level (REAL value)
Automatically starts motor when water level is low
Stops motor when water level is high
Manual START/STOP control via SCADA
Real-time data communication using OPC UA

Data Flow
PLC → OPC UA Server → Ignition SCADA → User Interface

 PLC Logic
IF Water Level < 20 → Motor ON
IF Water Level > 80 → Motor OFF
Manual override using Start/Stop buttons

SCADA Features
Start & Stop buttons
Real-time water level display
Motor status indication
Interactive UI design


Key Learning
OPC UA communication setup
PLC to SCADA integration
Real-time industrial data monitoring
Automation control logic design



Future Improvements
Add alarms & notifications
Data logging & analytics
Cloud integration (IoT)
Predictive maintenance using AI


 Author
Surendar
## 👨‍💻 Author
Surendar
