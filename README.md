# Traffic Light Detection with YOLOv8

This project implements a Traffic Light Detection System using the YOLOv8 object detection model.
It detects traffic lights in real-world images under diverse lighting and weather conditions using the Small Traffic Light Dataset (S2TLD).

Project Overview
Objective: Build a deep learning model that detects traffic lights in images.

Dataset: Small Traffic Light Dataset (S2TLD) — 4,500+ images with XML annotations (Pascal VOC format).

Approach:

Convert annotations from VOC (XML) to YOLO format.

Apply data augmentation to improve robustness.

Train YOLOv8 model and fine-tune hyperparameters.

Evaluate model using mAP, precision, and recall metrics.

Technologies & Tools
Languages: Python

Libraries & Frameworks:

PyTorch

YOLOv8 (Ultralytics)

OpenCV

Albumentations

xml.etree.ElementTree

tqdm

os, requests, zipfile

Techniques:

Object Detection

Data Augmentation

Hyperparameter Tuning

Model Evaluation (mAP, Precision, Recall)

Dataset
Name: Small Traffic Light Dataset (S2TLD)

Description: Contains 4,500+ images of traffic lights annotated in Pascal VOC XML format.

Scenarios: Day/night, sunny/rainy, different angles and distances.

Source: Provided within the notebook / project directory.
