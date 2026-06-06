#  Diabetic Retinopathy Detection Using Deep Learning

## Overview

Diabetic Retinopathy (DR) is one of the leading causes of vision impairment and blindness among diabetic patients worldwide. Early diagnosis plays a crucial role in preventing irreversible vision loss.

This project presents a deep learning-based approach for automated multi-class diabetic retinopathy classification using retinal fundus images. Multiple transfer learning architectures were evaluated and compared, including EfficientNetB0, ResNet50, MobileNetV2, and a proposed Hybrid EfficientNet–ResNet architecture with an Attention Mechanism.

The project was developed from scratch as part of an academic research and implementation study, focusing on model performance, class imbalance handling, and generalization analysis.

---

## Objectives

* Automate diabetic retinopathy detection using deep learning.
* Perform multi-class classification of retinal fundus images.
* Compare multiple state-of-the-art CNN architectures.
* Develop and evaluate a hybrid EfficientNet–ResNet architecture.
* Analyze model generalization using validation and test performance.
* Address class imbalance through weighted learning techniques.

---

## Dataset

**APTOS 2019 Blindness Detection Dataset**

Classes:

1. No DR
2. Mild DR
3. Moderate DR
4. Severe DR
5. Proliferative DR

The dataset consists of retinal fundus images labeled according to disease severity.

---

## Models Implemented

### 1. EfficientNetB0

* Transfer Learning
* Fine-Tuning
* Attention Mechanism
* Class Weighting

### 2. ResNet50

* Transfer Learning
* Residual Learning Architecture
* Comparative Analysis

### 3. MobileNetV2

* Lightweight CNN Architecture
* Comparative Benchmark Model

### 4. Proposed Hybrid Model

EfficientNetB0 + ResNet50

Features:

* Dual Feature Extraction
* Feature Fusion
* Attention Mechanism
* Fine-Tuning
* Regularization

---

## System Architecture

The project follows the pipeline:

Retinal Fundus Images
→ Data Preprocessing
→ Deep Learning Model
→ Feature Extraction
→ Classification
→ Performance Evaluation

---

### Key Findings

* EfficientNetB0 demonstrated the strongest generalization performance.
* The Hybrid Model achieved improved feature learning through feature fusion.
* Class weighting improved performance on minority classes.
* Validation accuracy alone was insufficient to evaluate model robustness.

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Research Contributions

* Comparative analysis of multiple CNN architectures.
* Hybrid EfficientNet–ResNet architecture.
* Attention-based feature refinement.
* Class imbalance handling using class weighting.
* Generalization analysis through validation and test evaluation.

---

## Future Improvements

* Vision Transformer (ViT) integration.
* Advanced attention mechanisms.
* Explainable AI techniques (Grad-CAM).
* Real-time clinical deployment.
* Mobile and cloud-based screening systems.

---

## Author

**Nikhil Kankipati**

UG Student | Deep Learning & AI Enthusiast

This project was developed as part of an academic research initiative focused on diabetic retinopathy detection using deep learning and transfer learning techniques.

---

## License

This project is intended for educational and research purposes.
