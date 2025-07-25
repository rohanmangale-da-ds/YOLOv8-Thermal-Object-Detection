# YOLOv8 Thermal Object Detection 🔥🎯

This project uses YOLOv8 to detect objects like **Person**, **Car**, **Bicycle**, etc. in thermal infrared images from the [HIT-UAV dataset](https://example.com).

---

## 🚀 Project Overview

- **Objective**: Detect key objects in thermal drone imagery.
- **Dataset**: HIT-UAV (High-altitude Infrared Thermal UAV Dataset)
- **Model**: [YOLOv8m](https://docs.ultralytics.com)
- **Classes**: Person, Car, Bicycle, OtherVehicle, DontCare
- **Tools**: PyTorch, OpenCV, Ultralytics YOLO, matplotlib

---

## 📁 Directory Structure

```bash
hit-uav/
├── images/
├── labels/
custom_images/         # Images used for custom testing
runs/detect/           # YOLO predictions
dataset.yaml           # YOLO format data config
train.py               # Script to train YOLOv8
predict.py             # Inference on custom images
utils.py               # Visualization tools


<img width="1636" height="2990" alt="image" src="https://github.com/user-attachments/assets/915488fa-c746-43ba-bf28-6a94eb3721a9" />

