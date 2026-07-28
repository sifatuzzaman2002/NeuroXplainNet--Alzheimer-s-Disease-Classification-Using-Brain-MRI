# NeuroXplainNet

NeuroXplainNet is an explainable deep learning framework for multiclass Alzheimer's disease classification using brain MRI images. The framework evaluates multiple transfer learning models and employs Grad-CAM to provide visual explanations for model predictions.

## Features

- Multiclass Alzheimer's disease classification
- Brain MRI image analysis
- Transfer learning using pretrained CNN models
- Fine-tuning for improved performance
- Explainable AI with Grad-CAM
- Performance comparison of multiple CNN architectures

## Dataset

The dataset contains brain MRI images categorized into four classes:

- Non-Demented
- Very Mild Demented
- Mild Demented
- Moderate Demented

Total images: **84,000**

Dataset split:

- Training: 67,200
- Validation: 8,400
- Testing: 8,400

Image size: **224 × 224**

## Models

The following pretrained CNN models were evaluated:

- VGG16
- MobileNetV2
- ResNet50
- DenseNet121
- InceptionV3
- Xception

Both pretrained and fine-tuned versions were compared.

## Best Performance

- Model: Fine-Tuned VGG16
- Accuracy: 99.00%
- Mean ROC-AUC: 0.9999

## Explainability

Grad-CAM is used to visualize the brain regions influencing the model's predictions, improving interpretability for Alzheimer's disease classification.

## Requirements

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn



## Disclaimer

This repository is intended for research and educational purposes only. It is not intended for clinical diagnosis or medical decision-making.
