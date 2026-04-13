# 🚦 Smart Traffic Management System using YOLOv8

## 📌 Project Overview
This project aims to develop an intelligent traffic management system that uses YOLOv8 for real-time vehicle detection and emergency vehicle prioritization. The system analyzes traffic density and dynamically controls traffic signals to reduce congestion and provide faster clearance for emergency vehicles.

---

## 🎯 Objectives
- Detect vehicles using YOLOv8
- Identify emergency vehicles (Ambulance, Fire Truck, Police)
- Analyze traffic density in multiple directions
- Automatically control traffic signals
- Provide real-time monitoring through a web dashboard

---

## 🛠️ Technologies Used
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Flask (Web Interface)
- HTML, CSS

---

## ⚙️ System Architecture
- Input: Traffic camera images/videos
- Processing: Image preprocessing using OpenCV
- Detection: YOLOv8 model
- Output:
  - Emergency vehicle detection
  - Traffic density analysis
  - Signal control

---

## 🚀 Features
- Real-time vehicle detection
- Emergency vehicle prioritization
- Adaptive traffic signal control
- Traffic density visualization
- Web dashboard for monitoring

---

## 📊 Results
- High accuracy vehicle detection
- Faster signal switching for emergency vehicles
- Reduced traffic congestion

---

## ▶️ How to Run the Project

### 1. Clone Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Run Application
```bash
python app.py
```

---

## 📷 Output Screenshots
<img width="1213" height="620" alt="image" src="https://github.com/user-attachments/assets/1d014c5c-0f5f-4aa3-8fc1-cdd878d703bb" />
Giving input feeds
<img width="1293" height="622" alt="image" src="https://github.com/user-attachments/assets/14562910-b1ed-4570-8a43-324d24bb1ead" />
Captures real-time video from multiple traffic cameras and converts it into frames for processing.Enhances video quality using resizing, normalization, noise reduction, and contrast improvement
<img width="1310" height="636" alt="image" src="https://github.com/user-attachments/assets/ece3eeef-3827-4fed-b4be-c0429cb166f2" />
Uses YOLOv8 to detect vehicles with bounding boxes.Separates emergency vehicles (ambulance, fire truck, police) from normal vehicles.
<img width="1265" height="611" alt="image" src="https://github.com/user-attachments/assets/ca841c51-7156-4881-add0-5fa9cbfd4f0b" />
Analyzes traffic density, validates detections across frames, and decides between emergency priority or normal traffic flow.Controls traffic signals dynamically based on decisions and displays results on a dashboard with data storage for monitoring


---

## 👩‍💻 Author
Vaishnavi K
Mohanraj N
Saran R
Vijayshankar M

---

## 📜 License
This project is for educational purposes.

