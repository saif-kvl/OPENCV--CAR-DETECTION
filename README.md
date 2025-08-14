# 🚗 Car Detection using OpenCV

This project implements a **Car Detection System** using **OpenCV** and **Haar Cascade Classifiers**. It can detect cars in real-time from a video feed or from a pre-recorded video file.

---

## 📌 Features

* Detects cars in real-time using your webcam or video file.
* Uses **Haar Cascade Classifier** for object detection.
* Easy to run and modify for other object detection tasks.
* Lightweight and works offline.

---

## 🛠️ Tech Stack

* **Python**
* **OpenCV**
* **Haar Cascade Classifier**

---

## 📂 Project Structure

```
📁 Car-Detection-OpenCV
│── car_detection.py       # Main Python script
│── cars.xml               # Haar cascade XML file for car detection
│── video.mp4               # (Optional) Sample video for detection
│── README.md               # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/Car-Detection-OpenCV.git
   cd Car-Detection-OpenCV
   ```

2. **Install dependencies**

   ```bash
   pip install opencv-python
   ```

3. **Run the project**

   ```bash
   python car_detection.py
   ```

---

## 📜 How it Works

1. Load Haar Cascade XML file for car detection.
2. Read video frames using OpenCV.
3. Convert frames to grayscale for better detection performance.
4. Use the classifier to detect cars and draw bounding boxes around them.

---

## 🚀 Future Improvements

* Use **Deep Learning (YOLO, SSD)** for more accurate detection.
* Implement **vehicle tracking**.
* Add **license plate recognition**.

---
