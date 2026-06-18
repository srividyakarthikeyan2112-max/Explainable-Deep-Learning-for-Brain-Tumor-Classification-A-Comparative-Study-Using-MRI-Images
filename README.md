
# 🧠 Explainable Deep Learning for Brain Tumor Classification Using MRI Images

## 📌 Overview

This research project presents an **Explainable Deep Learning Framework for Brain Tumor Classification using Magnetic Resonance Imaging (MRI) scans**. The study aims to develop an automated, reliable, and interpretable computer-aided diagnostic system that can accurately classify brain tumors and support radiologists in early diagnosis and clinical decision-making.

The framework performs a **comparative analysis of ResNet50 and EfficientNet (B0–B7) architectures** to identify the most accurate, computationally efficient, and clinically reliable model for MRI-based brain tumor classification. To improve transparency and trustworthiness, the project integrates **Gradient-weighted Class Activation Mapping (Grad-CAM)**, which visually highlights the regions of MRI images influencing the model's predictions.

---

## 🎯 Problem Statement

Brain tumor diagnosis using MRI scans is a complex and time-sensitive process that heavily depends on expert radiologists. Manual interpretation of MRI images is often time-consuming, susceptible to diagnostic variability, and constrained by the availability of specialized medical professionals. Furthermore, most existing AI-based diagnostic systems function as black-box models, limiting their adoption in real-world healthcare environments.

This research addresses these challenges by developing an explainable deep learning framework that systematically evaluates advanced deep learning architectures and generates interpretable visual explanations for their predictions.

---

## 🎯 Objectives

* Develop an automated MRI-based brain tumor classification framework using deep learning.
* Implement and compare **ResNet50** and **EfficientNet (B0–B7)** architectures.
* Evaluate model performance using comprehensive classification metrics.
* Generate explainable predictions using **Grad-CAM** visualizations.
* Identify the most accurate, efficient, and clinically interpretable model for brain tumor diagnosis.

---

## 🧬 Tumor Categories

The framework classifies MRI images into the following categories:

* **Glioma**
* **Meningioma**
* **Pituitary Tumor**
* **No Tumor (Healthy Brain)**

---

## 🔬 Methodology

### 1. Dataset Preparation

* MRI image acquisition
* Dataset organization and labeling
* Train, validation, and test split

### 2. Image Preprocessing

* Image resizing
* Normalization
* Data cleaning and standardization

### 3. Deep Learning Models

#### ResNet50

* Residual learning architecture
* Effective feature extraction
* Strong performance in medical imaging applications

#### EfficientNet (B0–B7)

* Compound scaling of depth, width, and image resolution
* High classification accuracy with fewer parameters
* Computationally efficient and scalable

### 4. Explainable Artificial Intelligence (XAI)

#### Grad-CAM

* Generates heat maps highlighting regions influencing predictions
* Improves model transparency and interpretability
* Enhances trust in AI-assisted clinical decision-making

---

## 📊 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

---

## 🛠️ Technology Stack

**Programming Language**

* Python

**Deep Learning Frameworks**

* TensorFlow
* Keras

**Libraries**

* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-learn

**Development Environment**

* Google Colab
* Jupyter Notebook

**Explainable AI**

* Grad-CAM

---

## 📈 Expected Outcomes

* Develop an intelligent MRI-based brain tumor classification framework.
* Determine whether **ResNet50** or **EfficientNet variants (B0–B7)** provide superior performance.
* Generate interpretable visual explanations for model predictions.
* Reduce diagnostic workload and support radiologists in clinical decision-making.
* Establish a reproducible and scalable framework for future medical imaging research.

---

## 🌍 Research Significance

### Clinical Significance

* Supports early detection of brain tumors
* Assists radiologists during diagnosis
* Improves diagnostic efficiency and reliability

### Technological Significance

* Provides a benchmark comparison of state-of-the-art deep learning architectures
* Demonstrates the practical application of Explainable AI in medical imaging

### Research Significance

* Bridges the gap between high classification accuracy and model interpretability
* Contributes toward trustworthy and clinically deployable AI systems
* Serves as a foundation for future research in explainable medical image analysis
