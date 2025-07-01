# Advanced-Machine-Learning-Algorithms-in-Predicting-Cloudy-and-Non-Cloudy-Areas
# 🌩️ Cloud Detection from Satellite Images using Deep Learning

## 🧠 Summary
This project applies four deep learning architectures (ResNet-50, VGG-19, Xception, YOLOv8) to detect cloudy vs non-cloudy regions in satellite images. It was developed as part of our final-year B.Tech capstone project at Lovely Professional University.

## 🚀 Models Used
- ResNet-50
- VGG-19
- Xception
- YOLOv8 (Best performing, 99% accuracy)

## 📊 Dataset
- Total Images: 5,631 (Cloudy, Desert, Green, Water)
- Sources: Google Maps, Kaggle Satellite Image Dataset (CB256 RSI v5.2)

## ⚙️ Tools & Libraries
- Python, TensorFlow, Keras, PyTorch, OpenCV
- Libraries: Numpy, splitfolders, matplotlib

## 📈 Results
| Model       | Accuracy |
|-------------|----------|
| ResNet-50   | 48%      |
| VGG-19      | 81%      |
| Xception    | 98%      |
| YOLOv8      | **99%**  |

## 📌 Highlights
- Real-time object detection with YOLOv8
- Applied image preprocessing: resizing, normalization, color jittering, augmentation
- Integrated performance metrics: accuracy, precision, recall, F1-score


