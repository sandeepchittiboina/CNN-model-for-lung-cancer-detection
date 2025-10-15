# CNN Model for Lung Cancer Detection

_Last updated: 2025-10-15_

Build a CNN model to classify images into the following classes: Benign, Normal, Adenocarcinoma, Large cell carcinoma, and Squamous Cell Carcinoma, using the data located at "data".

## Overview

This repository contains a Convolutional Neural Network (CNN) workflow for lung cancer detection from medical images. The notebook demonstrates data loading/preprocessing, model architecture, training, and evaluation steps.

## Features

- End-to-end pipeline: data preparation → modeling → evaluation
- Reproducible Jupyter Notebook
- Configurable hyperparameters (epochs, batch size, learning rate)
- Visualizations (training curves, evaluation outputs) if present

## Dataset

- **Mentions in notebook:** CT, Kaggle, dataset, test, train, val
- **Referenced paths:**
  - `[kagglehub.dataset_download("mdnafeesimtiaz/ct-scan-images-of-lung-cancer](https://www.kaggle.com/datasets/mdnafeesimtiaz/ct-scan-images-of-lung-cancer/data)`


## Model Architecture

A CNN-based classifier implemented in deep learning framework(s) used in the notebook. Document the layers (conv, pooling, batch norm, dropout), activation functions, and final classification head here.

## Hyperparameters

- **batch_size**: `batch_size)`
- **image_size**: `(img_height, img_width),`
- **epochs**: `epochs`

## How to Run

1. Create and activate a Python environment (e.g., `conda` or `venv`).
2. Install dependencies:
   ```bash
pip install kagglehub tensorflow
   ```
3. Open the notebook:
   ```bash
   jupyter notebook CNN_model_for_lung_cancer_detection.ipynb
   ```
4. Run cells in order to preprocess data, train the model, and evaluate results.

## Reported Metrics (auto-extracted)
- 39/39 ━━━━━━━━━━━━━━━━━━━━ 36s 939ms/step - accuracy: 0.8838 - loss: 0.2868 - val_accuracy: 0.8632 - val_loss: 0.3346
- 39/39 ━━━━━━━━━━━━━━━━━━━━ 36s 931ms/step - accuracy: 0.9189 - loss: 0.2068 - val_accuracy: 0.8697 - val_loss: 0.3318
- 39/39 ━━━━━━━━━━━━━━━━━━━━ 36s 933ms/step - accuracy: 0.9419 - loss: 0.1401 - val_accuracy: 0.9153 - val_loss: 0.2186
- 39/39 ━━━━━━━━━━━━━━━━━━━━ 41s 928ms/step - accuracy: 0.9501 - loss: 0.1404 - val_accuracy: 0.8893 - val_loss: 0.3372
- 39/39 ━━━━━━━━━━━━━━━━━━━━ 37s 940ms/step - accuracy: 0.9661 - loss: 0.1140 - val_accuracy: 0.9414 - val_loss: 0.1673

## Project Structure

```
.
├── CNN_model_for_lung_cancer_detection.ipynb  # main notebook
└── README.md        # this file
```

## Key Dependencies (detected)

kagglehub, tensorflow

## Notes & Next Steps

- Add dataset source and licensing details
- Save trained weights and document how to load them
- Export an inference script for batch or real-time predictions
- Add unit tests and CI if this will be maintained

## License

Choose a license (e.g., MIT) and add it here.
