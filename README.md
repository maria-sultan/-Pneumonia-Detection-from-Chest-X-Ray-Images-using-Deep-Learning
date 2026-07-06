# 🫁 Pneumonia Detection from Chest X-Ray Images using Deep Learning

A deep learning project for automated **pneumonia detection** from chest X-ray images using multiple neural network architectures. This project compares the performance of a **Custom CNN**, **ResNet50 (Transfer Learning)**, and a **CNN-Transformer Hybrid** model for binary image classification.

---

## 📌 Project Overview

This project implements an end-to-end deep learning pipeline for detecting pneumonia from chest X-ray images. It includes:

- Dataset preprocessing and visualization
- Image augmentation
- Class imbalance handling
- Multiple deep learning architectures
- Hyperparameter tuning
- Optimizer comparison
- Transfer learning
- Model evaluation and comparison
- Overfitting and vanishing gradient mitigation

---

## 🚀 Features

- Image preprocessing and normalization
- Automatic train/validation/test splitting (70/20/10)
- Data augmentation
- Class weight balancing
- Custom CNN implementation
- ResNet50 transfer learning with fine-tuning
- CNN + Transformer hybrid architecture
- Optimizer comparison (Adam, SGD, RMSprop)
- Hyperparameter tuning
- Early stopping and learning rate scheduling
- Confusion matrix and ROC curve visualization
- Accuracy, Precision, Recall, F1-score, and AUC evaluation

---

## 🧠 Models Implemented

### 1. Custom CNN
- Built from scratch
- Batch Normalization
- Dropout Regularization
- Global Average Pooling

### 2. ResNet50
- ImageNet pretrained weights
- Transfer Learning
- Fine-tuning

### 3. CNN + Transformer Hybrid
- CNN feature extractor
- Multi-Head Self Attention
- Transformer Encoder Blocks
- Positional Embeddings

---

## 📂 Dataset

**Chest X-Ray Images (Pneumonia)**

Source:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Classes:
- NORMAL
- PNEUMONIA

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

---

## ⚙️ Training Techniques

- Data Augmentation
- Early Stopping
- Model Checkpointing
- Learning Rate Scheduling
- Class Weights
- Hyperparameter Tuning
- Optimizer Comparison

---

## 📈 Model Comparison

The project compares the three architectures based on:

- Accuracy
- F1-score
- AUC
- Model Complexity
- Number of Parameters
- Training Performance

---

## 📁 Project Structure

```
├── pneumonia_dl_project.py
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/pneumonia-detection-deep-learning.git

cd pneumonia-detection-deep-learning
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python pneumonia_dl_project.py
```

---

## 📚 Learning Outcomes

This project demonstrates:

- Medical image classification
- Transfer Learning
- Vision Transformers
- CNN architectures
- Deep Learning optimization
- Performance evaluation
- Model comparison

---

## 👩‍💻 Author

**Maria Sultan**

Software Engineering Student

---

## 📜 License

This project is intended for educational and research purposes.
