# 🚁 YOLOv8 Military Helicopter Detection  
Detect and classify **military helicopters** in aerial images using **Ultralytics YOLOv8**, fine-tuned on a custom dataset.  

---

## 📌 Project Overview  

This repository provides a **YOLOv8-based object detection pipeline** for identifying military helicopters. The model is trained using a **Roboflow custom dataset** and produces high-accuracy predictions with bounding boxes.  

- 🔍 **Model**: YOLOv8 (Ultralytics)  
- 📂 **Dataset**: Roboflow (`aircraft-detection-swor3`)  
- 🖼️ **Task**: Object Detection  
- 🖥️ **Environment**: Google Colab with NVIDIA GPU  

---

## 🚀 Features  

- ✅ Dataset auto-download from Roboflow  
- ✅ YOLOv8 training & evaluation (custom parameters)  
- ✅ Performance metrics: Precision, Recall, mAP  
- ✅ Training visualizations (loss curves, confusion matrix, prediction samples)  
- ✅ Inference pipeline for test images  

---
Training configuration:

- Epochs: 50
- Image size: 800px
- Base model: yolov8s.pt
- Results are saved under:
runs/detect/train/
 
---

## ⚙️ Installation  

- bash
git clone https://github.com/yourusername/yolov8-military-helicopter-detection.git
cd yolov8-military-helicopter-detection
pip install ultralytics==8.0.196 roboflow

---

## 📊 Results & Metrics

After training, YOLOv8 reports standard detection metrics.

- Metric	Value (example)
- Precision (P) :	0.91
- Recall (R) :	0.88
- mAP50	: 0.93
- mAP50-95 :	0.81
- F1-Score :	0.89

<img width="1760" height="930" alt="Screenshot 2024-09-10 093753" src="https://github.com/user-attachments/assets/ebc93825-92e5-469c-9215-1c34e01b4455" />
<img width="1760" height="930" alt="Screenshot 2024-09-10 093700" src="https://github.com/user-attachments/assets/94e8ea4f-eaf7-4a98-bd31-96e6f003fcc7" />
<img width="1760" height="930" alt="Screenshot 2024-09-10 093637" src="https://github.com/user-attachments/assets/56382cd7-71da-4e1b-8ae9-18949fa448b1" />
<img width="1760" height="930" alt="Screenshot 2024-09-10 093552" src="https://github.com/user-attachments/assets/3ff169a5-afde-402d-b453-ae795217d0b7" />
<img width="1526" height="759" alt="Screenshot 2024-09-22 193441" src="https://github.com/user-attachments/assets/ec1e3303-d6a9-4dc0-98d1-43450dde3b47" />
