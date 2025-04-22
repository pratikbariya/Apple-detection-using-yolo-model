# 🍎 Apple Detection and Measurement using YOLOv11

This project focuses on detecting apples using the YOLOv11 object detection model and paves the way for future measurement tasks such as calculating radius and diameter via segmentation and post-processing.

---

## 🧠 What is Object Detection?

**Object Detection** is a computer vision technique that allows us to identify and locate objects within an image or video. Unlike classification (which tells what is in an image), object detection tells **what** and **where**.

Each object is identified with:
- A **class label** (e.g., Apple)
- A **bounding box** with coordinates (x, y, width, height)

---

## 🎯 Benefits of Object Detection

- 🔍 **Precision**: Detects individual objects within complex scenes.
- 📏 **Measurable**: Enables further analysis like shape, size, and distance.
- 🤖 **Automation**: Powers applications like industrial inspection, autonomous vehicles, and smart agriculture.
- 📦 **Scalable**: Easily extended to detect multiple object classes in real-time.

---

## 📦 Dataset

- Source: [Roboflow](https://roboflow.com/)
- Workspace: `tntra-oubra`
- Project: `diameter-counting`
- Version: 3
- Format: YOLOv11-compatible

📽️ **How to Prepare and Annotate Your Dataset:**  
Watch this video tutorial: [How to Annotate Images for Object Detection](https://www.youtube.com/watch?v=a3SBRtILjPI)

---

## 🧰 Tech Stack

- Python 3.11+
- [YOLOv11](https://github.com/ultralytics/ultralytics)
- Roboflow SDK
- Ultralytics training framework
- Google Colab (for training and evaluation)

---

## 🚀 Getting Started

### 1. Install Required Packages

```bash
pip install roboflow
pip install ultralytics
