# A Context Aware Emergency Priority Network for Traffic Incident Detection and Intelligent Emergency Response using Multimodal Audio Analytics 

## Overview

This repository contains the implementation of CEPN (Context-Aware Emergency Prediction Network), a multimodal framework for traffic-incident severity assessment and intelligent emergency response.

The proposed framework combines visual traffic information with acoustic information to estimate traffic-incident severity and support emergency decision-making.

## Research Paper

**Title:** A Context Aware Emergency Priority Network for Traffic Incident Detection and Intelligent Emergency Response using Multimodal Audio Analytics

## Methodology

The CEPN framework consists of the following major components:

1. Traffic video preprocessing
2. Vehicle detection using YOLOv8
3. Visual feature extraction
4. Acoustic feature extraction
5. Multimodal feature fusion
6. Dynamic Emergency Priority Score (DEPS)
7. Traffic-incident severity classification
8. Emergency Decision Engine
9. SHAP-based explainability
10. Performance evaluation

## Visual Features

The implementation extracts traffic-related visual information including:

- Vehicle count
- Vehicle density
- Maximum vehicle count

## Acoustic Features

The acoustic analysis uses:

- Mel-Frequency Cepstral Coefficients (MFCC)
- Root Mean Square (RMS) energy
- Zero-Crossing Rate (ZCR)
- Spectral Flux

## Dataset

The experiments use the AV-TAU dataset.

The dataset is not redistributed in this repository. Users should obtain the dataset from the original dataset provider and comply with its access and usage conditions.

## Implementation

The main implementation is provided as a Google Colab-compatible Jupyter Notebook:

`CEPN_Project.ipynb`

The notebook contains the preprocessing, feature extraction, DEPS computation, machine-learning classification, explainability analysis, and evaluation procedures used in the study.

## CEPN Architecture

![CEPN Architecture](architecture.jpeg)

## Feature Importance

![Feature Importance](feature_importance.jpeg)

## Confusion Matrix

![Confusion Matrix](confusion_matrix.jpeg)

## Requirements

The implementation uses Python and commonly used machine-learning and multimedia-processing libraries, including:

- Python
- NumPy
- Pandas
- OpenCV
- Librosa
- Scikit-learn
- Matplotlib
- YOLOv8 / Ultralytics
- SHAP

## Results

The experimental evaluation includes:

- Classification accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Feature importance
- Comparison with a visual-only baseline

## Google Colab Implementation

The complete implementation of the proposed CEPN framework and the experimental workflow are provided in the following Google Colab notebook. The notebook contains the preprocessing, visual and acoustic feature extraction, DEPS computation, Random Forest classification, SHAP-based analysis, and evaluation procedures used in the study.

**Google Colab Notebook:**  
[Open CEPN Implementation](https://colab.research.google.com/drive/160iTtJ-4iPuErJjMhE3sGaCVHumBI1H1?usp=sharing)
