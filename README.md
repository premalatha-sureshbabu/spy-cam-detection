# 🕵️‍♂️ Spy Camera Detection System

A real-time Spy Camera Detection System that uses deep learning and computer vision techniques to identify hidden or suspicious cameras in an environment. Built with Python and powered by a pre-trained object detection model (e.g., SSD with MobileNet), this tool helps enhance privacy and security in sensitive areas.

## 📌 Features

- 📷 Real-time camera feed processing
- 🧠 Deep learning-based object detection using COCO SSD model
- 🔍 Detects hidden cameras and suspicious devices
- 💻 Simple GUI or terminal-based interface
- 🗂️ Logs detections with timestamps and confidence scores

## 🚀 How It Works

1. Captures video frames from a webcam or connected camera.
2. Processes each frame using a pre-trained SSD (Single Shot Detector) model.
3. Identifies and highlights objects categorized as cameras or electronic devices.
4. Raises alerts or logs when suspicious objects are detected.

## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- TensorFlow / TFLite / PyTorch (based on implementation)
- Pre-trained COCO SSD model (MobileNetV2/ResNet)
- NumPy, time, and other utility libraries

