---
title: "Time Series - Terrain Identification from Time Series Data"
description: "Developed a model to detect Terrain from the IMU data from prosthetics."
draft: false
tags: ["Python", "Tensorflow", "LSTM", "Deep Learning", "Neural Network", "Time Series", "Bi-LSTM"]
showToc: false
weight: 102
# cover:
#     image: "projects/automated-image-captioning/cover.jpg"
--- 
### 🔗 [Github](https://github.com/kartikrawool/Brain-Tumor-Segmentation)

## Description
- Preprocessed 40Hz **Inertial Measurement Unit (IMU)** data to match the 10Hz frequency of labels using nearest
label upsampling.
- Trained Long Short-Term Memory (LSTM) and Bidirectional LSTM (Bi-LSTM) models on windowed 2-sec data,
achieving an impressive **85% F1 score** on testing data.