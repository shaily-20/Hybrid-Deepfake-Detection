# Deepfake Detection Using Hybrid Deep Learning Framework

## Overview

This project presents a **hybrid deepfake detection framework** that leverages CNN-based feature extraction and physiological cues to improve detection accuracy and robustness. Deepfake media, which is increasingly realistic, poses serious cybersecurity and misinformation risks. Our approach combines multiple neural networks with Eye Movement Analysis to enhance detection effectiveness.

## Features

- **Hybrid Model Architecture:** Integrates ResNet50 and MesoNet4 for high-level spatial and low-resolution feature detection.  
- **Physiological Cue Analysis:** Uses blink rate and gaze shift inconsistencies to improve model performance.  
- **High Accuracy:** Achieves **97.61% accuracy** on multiple datasets including Deepfake-and-Real Images, UADFV, and FaceForensics++.  
- **Explainable AI:** Grad-CAM visualization improves model interpretability and transparency.  

## Architecture

- **ResNet50:** Extracts high-level spatial features.  
- **MesoNet4:** Optimized for detecting low-resolution manipulations.  
- **Eye Movement Analysis Module:** Detects physiological inconsistencies in facial behavior.  

## Folder Structure

deepfake-detection/
│
├── data/ # Datasets (Deepfake-and-Real, UADFV, FaceForensics++)
├── models/ # Saved trained models
├── src/ # Source code
│ ├── train.py # Training script
│ ├── evaluate.py # Evaluation script
│ └── grad_cam.py # Grad-CAM visualization script
├── requirements.txt # Python dependencies
└── README.md


## Installation

1. Clone the repository:

# git clone <your-repo-link>
# cd deepfake-detection
# pip install -r requirements.txt

## Download Project

You can download the full project files from Google Drive:

[📂 Download the Deepfake Detection Project]([https://drive.google.com/your-link-here](https://drive.google.com/drive/folders/18KO7cQpzoEToGY2YhK7x5dsDMszrS69V?usp=drive_link))
