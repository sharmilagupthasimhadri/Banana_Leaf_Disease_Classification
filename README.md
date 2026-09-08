# Banana Leaf Disease Classification 🍌🌿

## Project Overview
This project classifies banana leaf diseases using Machine Learning and Deep Learning techniques.

Two approaches were implemented and compared:

- HOG (Histogram of Oriented Gradients) + SVM
- MobileNetV2 Transfer Learning

## Models Used

### 1. HOG + SVM
Traditional machine learning approach using HOG feature extraction followed by Support Vector Machine classification.

### 2. MobileNetV2
A pre-trained MobileNetV2 model was used with transfer learning for image classification.

## Results

| Model | Test Accuracy |
|---|---:|
| HOG + SVM | 48.39% |
| MobileNetV2 | 76.00% |

MobileNetV2 achieved better classification performance than the traditional HOG + SVM approach.

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- NumPy
- Matplotlib
- Google Colab

## Dataset

The dataset contains images of banana leaves belonging to different disease classes.

## Project Files

- `Banana_Leaf_Disease_Classification.ipynb` — Complete implementation
- `banana_mobilenetv2.h5` — Trained MobileNetV2 model

## Conclusion

The results show that transfer learning using MobileNetV2 provides better performance for banana leaf disease classification compared with the HOG + SVM approach.
