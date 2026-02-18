# Progenitor: Offroad Segmentation with DINOv2

This repository contains training and evaluation scripts for offroad semantic segmentation using **DINOv2 (vits14)** as a feature extractor.

## 📊 Results
- **Validation Loss:** 0.8170
- **Pixel Accuracy:** 70.28%
- **Mean IoU:** 31.99%

## 📂 Key Files
- `train_segmentation.py`: Main training script.
- `result.md`: Detailed performance metrics and graphs.
- `train_stats/`: Folder containing loss and accuracy curves.

## 🚀 Usage
1. Install dependencies: `pip install torch torchvision numpy`
2. Run training: `python train_segmentation.py`