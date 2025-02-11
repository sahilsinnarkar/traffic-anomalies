# 🚗 Color Car Number Plate & Vehicle Counting using YOLO 🎯

## 📋 **Project Overview**
This project focuses on **detecting car number plates, identifying their colors**, and **counting the number of vehicles in a frame** using **YOLO (You Only Look Once)**, an advanced object detection algorithm. The system processes video streams or images to provide real-time analytics for traffic monitoring.

---

## 🧠 **Key Features**
- ✅ **Vehicle Detection** using YOLOv9
- 🎨 **Color Detection** of Car Number Plates
- 🔢 **Vehicle Counting** in Real-Time Frames
- 📷 **Supports Video and Image Inputs**

---

## 🚀 **Tech Stack**
- **YOLOv9** - Object Detection
- **OpenCV** - Image Processing
- **NumPy** - Data Manipulation
- **Python** - Programming Language

---

## ⚙️ **Installation & Setup**
1️⃣ **Clone the Repository:**  
```bash
git clone git@github.com:sahilsinnarkar/traffic-anomalies.git
cd traffic-anomalies
```

2️⃣ **Create Virtual Environment (Optional but Recommended):**  
```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

3️⃣ **Install Dependencies:**  
```bash
pip install -r requirements.txt
```

4️⃣ **Download YOLOv9 Weights:**  
Place the YOLOv9 weights in the `models/` directory. You can download them from the [official YOLO repository](https://github.com/WongKinYiu/yolov9).
---

## 🔍 **How It Works**
1. **Vehicle Detection:** YOLOv9 identifies vehicles in each frame.
2. **Number Plate Detection:** Extracted using bounding boxes.
3. **Color Detection:** Utilizes HSV color space for accurate color recognition.
4. **Vehicle Counting:** Objects are tracked across frames to count unique vehicles.

---

## 📈 **Sample Results**
- ✅ **Detected Vehicles with Bounding Boxes**
- 🎯 **Color-Labeled Number Plates**
- 🔢 **Live Vehicle Count Display**

![image](https://github.com/user-attachments/assets/472953bc-d546-4ef4-9cbc-c505540b5b03)

![image](https://github.com/user-attachments/assets/1b6b464c-3c0f-4a5f-9f9d-ce8748eff8e6)

