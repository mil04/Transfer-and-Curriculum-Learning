# Transfer Learning and Curriculum Learning for CNN and Transformer Architectures

## Overview
This project explores the use of transfer learning and curriculum learning for Convolutional Neural Networks (CNNs) and transformer architectures. Our main goal is to improve model performance on image classification tasks by leveraging pre-trained models and structured learning approaches.

## Features
- **Transfer Learning**: Fine-tune pre-trained models on new datasets to enhance performance.
- **Curriculum Learning**: Implement manual and self-paced learning strategies to improve model training efficiency.
- **Explainable AI (XAI)**: Use LIME to understand model behavior and interpret predictions.

## Datasets
1. **Describable Textures Dataset (DTD)**: 5640 images categorized into 47 classes.
2. **ImageNet**: A large-scale dataset with 14,197,122 images across 21,841 categories.
3. **RSSCN7**: 2800 satellite images divided into 7 classes, used for transfer and curriculum learning.

## Models
### Transformers
- **Vision Transformer (ViT)**: Trained from scratch and fine-tuned on the DTD and RSSCN7 datasets.

### Convolutional Neural Networks
- **ResNet18**: Pre-trained on ImageNet and DTD, and fine-tuned on RSSCN7.

## Curriculum Learning
1. **Manual Division**: Images are manually divided into easy, medium, and hard sets.
2. **Self-Paced Learning**: The model dynamically adjusts the training set based on its performance.

## Results
- **Transfer Learning**: Both CNN and Transformer models show improved performance when fine-tuned on specific datasets.
- **Curriculum Learning**: Models trained with curriculum learning strategies demonstrated better stability and accuracy.

## Collaborators
- **Bokhan Katsiaryna**
- **Pahasian Milanna**
- **Rafał Pyzowski**
-  **Jakub Sawicki**
