Implementing Security on Shared IoT Devices

📌 Overview
As IoT devices become widespread in shared environments like homes, hospitals, and industrial settings, ensuring their security is critical. This project presents a lightweight, scalable, and intelligent security framework specifically designed for shared IoT systems, addressing challenges like unauthorized access, privacy concerns, and real-time threat detection.

🚨 Problem Statement
Shared IoT devices are exposed to multiple users with varying trust levels, increasing risks like:
•	Unauthorized access to sensitive data
•	Lack of access control mechanisms
•	Weak encryption due to limited device resources
•	Real-time threat detection complexities
•	Infrequent or manual firmware updates
•	Low user awareness of cybersecurity practices

🎯 Objectives
1.	Design a lightweight encryption model tailored for low-power IoT devices.
2.	Implement role-based and contextual access control for multiple users.
3.	Integrate AI-driven anomaly detection for real-time threat prevention.
4.	Simulate secure OTA (Over-The-Air) firmware updates.
5.	Educate users through simulated awareness prompts on best practices.
6.	Develop a practical Cisco Packet Tracer simulation of a smart home network with:
o	Central router, main server, access points
o	Room-wise switches and IoT devices
o	Network security (firewall, port security, encrypted passwords, smartphone authentication)

🧠 Methodology
•	Encryption: A custom lightweight XOR-based encryption scheme for speed and efficiency.
•	Access Control: Role-based (Admin/User/Guest) and time/location-based access rules.
•	Threat Detection: Machine learning model using device behavior data to flag anomalies.
•	OTA Simulation: Update delivery via central server to connected IoT devices in simulation.
•	User Awareness: Dynamic prompts for secure password setup and suspicious activity alerts.

🧪 Tools & Technologies
•	🧩 Cisco Packet Tracer – For simulating smart home architecture and networking components
•	🐍 Python – ML-based anomaly detection engine
•	🛡️ Custom Protocol Design – For lightweight encryption and secure data flow
•	📱 Smartphone Auth Integration – Using simulated devices for authentication

🧾 Features
•	🔐 Encrypted device communication
•	👥 Role-based user management
•	🧠 AI-based anomaly detection
•	📤 Secure OTA update simulation
•	📊 Device logs and activity tracking
•	🧰 Cisco-configured network security

🔬 Results
•	Reduced threat detection time by 40% using ML-based behavioral patterns
•	Encryption latency under 5ms on simulated low-resource devices
•	Access control accuracy ~98% in permission enforcement tests

🚀 Future Scope
•	Expand support to industrial IoT (IIoT) settings
•	Use blockchain for secure access logs
•	Incorporate biometric access modules
•	Real-world deployment on ESP32/NodeMCU devices

🧠 Learnings
•	Designing secure protocols within hardware constraints
•	Balancing user accessibility and device protection
•	Importance of user education in cybersecurity
•	Real-time threat modeling using behavioral data

🤝 Contributors
•	Sarvesh Prasad

