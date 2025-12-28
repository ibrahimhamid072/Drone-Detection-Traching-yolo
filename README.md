# 🚁 Real-Time Drone Detection & Tracking System

![YOLOv11](https://img.shields.io/badge/YOLOv11-SOTA_Detection-ff5c5c?style=for-the-badge&logo=ultralytics)
![Tracking](https://img.shields.io/badge/Tracking-ByteTrack-blue?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-Roboflow-purple?style=for-the-badge&logo=roboflow)

## 📌 Project Overview
An advanced Computer Vision system developed to detect and track Unmanned Aerial Vehicles (UAVs/Drones) in complex environments. By integrating the state-of-the-art YOLOv11 architecture with the robust ByteTrack algorithm, this project ensures high-speed inference and consistent object identity maintenance, making it highly suitable for airspace monitoring and security applications.

## 🎥 Demo In Action
> Real-time tracking results showing ID assignment and trajectory.
> ![IMG_00051-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/685ca8a4-ce25-4f2a-8bb7-d45cdba70d39)


## 🎯 Key Features
* State-of-the-Art Detection: Utilizes YOLOv11, the latest and most efficient iteration of the YOLO family, for cutting-edge detection performance.
* Precision Tracking: Implements ByteTrack, a powerful multi-object tracking algorithm that handles occlusion and low-confidence detections effectively.
* Robust Dataset: Trained on a comprehensive dataset from Roboflow, consisting of over 6,000 images, ensuring the model generalizes well across different backgrounds and distances.
* High-Performance Training: Leveraged Kaggle's Cloud GPUs for efficient model convergence and hyperparameter tuning.

## 📊 Dataset & Training Details
The model's robustness is built upon a high-quality data pipeline:
* Source: Roboflow Universe.
* Volume: 6,000+ Annotated Images.
* Model Version: YOLOv11 (Ultralytics).
* Objective: Minimized false positives while maximizing detection recall for small, fast-moving aerial objects.

## 🛠️ Tech Stack
* Deep Learning Framework: PyTorch
* Model Architecture: YOLOv11
* Tracking Algorithm: ByteTrack
* Data Management: Roboflow
* Development Platform: Kaggle Notebooks
* Video Processing: OpenCV

## 👨‍💻 Author
Ibrahim
Electrical and Electronics Engineering Student | computre vision 
