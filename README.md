# YOLO v1 from Scratch
An implementation of the YOLO v1 (You Only Look Once) object detection algorithm from scratch, trained and tested on the Pascal VOC dataset.

## Project Overview
This repository contains a fully custom implementation of the YOLO v1 algorithm as outlined in the YOLO v1 research paper. YOLO v1 is one of the first convolutional neural networks designed for real-time object detection, framing detection as a single regression problem directly from image pixels to bounding box coordinates and class probabilities.

## Key Features
- End-to-end training and inference pipeline using YOLO v1.
- Implemented from scratch in Python with PyTorch.
- Trained on the Pascal VOC dataset, a standard benchmark for object detection tasks.
## Dataset Preparation
- Download the Pascal VOC dataset (VOC 2007 or VOC 2012).
## Model Architecture
YOLO v1 divides each input image into an SxS grid. Each grid cell predicts B bounding boxes and confidence scores for those boxes, along with class probabilities. Notable layers include:

- Convolutional Layers: for feature extraction.
- Fully Connected Layers: for final output predictions.
## References
Redmon, J., Divvala, S., Girshick, R., & Farhadi, A. (2016). You Only Look Once: Unified, Real-Time Object Detection. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR).
