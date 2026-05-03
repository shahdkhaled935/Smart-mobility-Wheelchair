# Smart Mobility Wheelchair

## 🎯 Problem Statement
People with mobility impairments face challenges in moving independently and safely in unknown environments.  
This project aims to design an intelligent mobility system that enhances autonomy and safety.

---

## 📌 Overview
This project is a Smart Mobility Wheelchair system built using ROS 2 for autonomous navigation and environment understanding.

It integrates LiDAR sensors and SLAM algorithms to perceive the environment, build real-time maps, and avoid obstacles during movement.

---

## 🧠 System Architecture
The system is structured into three main layers:

- **Sensor Layer:** LiDAR for environment perception  
- **Processing Layer:** ROS 2 nodes for SLAM and navigation logic  
- **Control Layer:** Motor commands for movement  

Data flows from sensors → SLAM mapping → decision-making → motion control.

---

## 🧠 Design Decisions
ROS 2 was selected due to its modular architecture and real-time communication capabilities, which are essential for robotics applications.

SLAM was used to enable simultaneous mapping and localization in unknown environments without requiring pre-built maps.

LiDAR was chosen for its reliability in distance measurement and obstacle detection compared to camera-only solutions.

---

## ⚠️ System Limitations
- The system was tested in controlled/simulated environments  
- Performance depends on sensor quality and environment conditions  
- Real-world deployment would require additional safety layers  

---

## 🚀 Features
- Autonomous navigation in unknown environments  
- Real-time obstacle detection and avoidance  
- SLAM-based mapping  
- Sensor-driven decision making  

---

## ⚙️ Challenges & Solutions
- **Noisy sensor data:** Handled using filtering techniques  
- **Navigation delay:** Improved ROS 2 communication efficiency  
- **Mapping stability:** Tuned SLAM parameters for better accuracy  

---

## 🛠️ Technologies Used
- ROS 2  
- Python / C++  
- LiDAR Sensor  
- SLAM algorithms  

---

## 👩‍💻 My Contribution
- Developed navigation logic using ROS 2  
- Integrated LiDAR sensor for perception  
- Worked on SLAM-based mapping  
- Tested system in controlled environments  

---

## 📊 Outcome
- Successful autonomous navigation in testing environments  
- Real-time mapping of surroundings  
- Stable obstacle avoidance behavior  

---

## 📈 Engineering Insight
This project demonstrates understanding of robotics system integration, including perception, mapping, and control pipelines using ROS 2.

It focuses on modular design and real-time decision-making for autonomous mobility applications.

---

## 📷 Results
![Wheelchair](wheelchair.jpeg)  
![Mapping](mapping.jpeg)

---

## 🎥 Demo
https://github.com/shahdkhaled935/Smart-mobility-Wheelchair/blob/main/GRADproject.mp4
