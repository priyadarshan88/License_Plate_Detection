# License Plate Detection using YOLOv8

A project to detect and localize license plates from vehicle images/videos using the YOLOv8 object detection model.

[Watch a sample demo video here](https://drive.google.com/file/d/1JbwLyqpFCXmftaJY1oap8Sa6KfjoWJta/view?usp=sharing)

---

## Introduction

This project uses the YOLOv8 architecture to detect license plates from input images or video streams. The model is trained (or fine-tuned) on a dataset of vehicles with annotated license plates. The end goal is a ready-to-deploy pipeline that can be used in surveillance, traffic monitoring, parking automation, etc.

---

## Features

- Real-time detection of license plates  
- Support for image and video inference  
- Bounding box output (and optionally, cropping of license plate region)  
- Easy to extend, retrain, and deploy  

---

## Requirements

- Python 3.8+  
- Ultralytics YOLOv8 (or ultralytics package)  
- OpenCV  
- Other dependencies, e.g.:  
  ```text
  numpy
  torch
  torchvision
  pandas
  matplotlib
