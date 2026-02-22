# 🧭 Guidex – Smart Vision Aid for the Visually Impaired
## 📌 Overview
Guidex is a vision-powered smart navigation system designed to assist visually impaired individuals using real-time object detection and voice-based directional guidance.
The system uses an ESP32-CAM module to detect obstacles and classify their position into left, center, or right zones, providing clear audio feedback for safe navigation.
## 🚀 Problem Statement
Visually impaired individuals face difficulties navigating unfamiliar or crowded environments. Traditional tools like walking sticks do not provide directional awareness or object identification.

Guidex enhances independence by combining embedded systems and computer vision to deliver intelligent audio navigation assistance.
## 💡 Key Features
- 📷 Real-time vision capture using ESP32-CAM  
- 🔊 Voice-based directional feedback (Left / Center / Right)  
- 🧠 Zone-based obstacle classification  
- 📡 Wireless operation  
- 🚫 No vibration alerts – clear voice-only guidance  
## 🛠️ Hardware Used
- ESP32-CAM Module  
- FTDI Programmer  
- Audio Output Module  
- Speaker / Earphones  
- Power Supply  
## 💻 Software & Technologies
- Arduino IDE  
- Embedded C  
- Computer Vision Concepts  
- IoT Concepts  
## 🧠 Working Principle
1. ESP32-CAM captures live video frames.  
2. The frame is processed for obstacle detection.  
3. The screen is divided into three zones:
   - Left  
   - Center  
   - Right  
4. Based on obstacle position, the system gives voice feedback:
   - "Obstacle on Left"
   - "Obstacle Ahead"
   - "Obstacle on Right"
## 🔮 Future Improvements
- 🌍 GPS Integration  
- 💧 Water Detection Sensor  
- 🌙 Infrared Night Detection  
- 📱 Mobile Application Integration  
- 🧠 Advanced AI-based object classification  
## 🏆 Developed During
HackGenesis Hackathon – June 21  
## 👩‍💻 Author
Haasini Nagidi  
Computer Science Engineering Student  