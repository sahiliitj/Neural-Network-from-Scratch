# 🤖 Neural Network from Scratch – Multi-Class Classification
 
> **Author:** Sahil Sharma  
> **Program:** M.Sc - M.Tech (Mathematics & Data and Computational Sciences)  
> **Institute:** Indian Institute of Technology, Jodhpur  
---

## 📝 Project Overview

This project focuses on designing and training a **feedforward neural network from scratch** in Python to perform **multi-class classification** on the MNIST-like dataset of digit images. It explores:

- Building a neural network from first principles
- Training using gradient descent and backpropagation
- Experimenting with different train-test split ratios
- Evaluating model performance with accuracy curves and confusion matrices

---

## 📁 Dataset Description

- **Dataset Size:** 70,000 grayscale images
- **Image Dimensions:** 28 × 28 pixels
- **Labels:** Digits from 0 to 9 (10 classes)

---

## 🔍 Task Highlights

### 🛠️ 1. Building the Neural Network

📎 [Colab Notebook](https://colab.research.google.com/drive/1qVt1Q5ppGDyFZBtb0kwuEls7uu2VpiAg?usp=sharing)

#### 1.1 Exploratory Data Analysis

- Count of each digit label
- Histogram of label frequencies
- Pixel intensity distribution

#### 1.2 Task Performed

- Built a **feedforward neural network** from scratch
- Implemented:
  - Forward propagation
  - Backpropagation
  - Weight and bias updates using **Gradient Descent**
  - Evaluation using **Cross-Entropy Loss** and **Accuracy**
  - Plotted **Confusion Matrix** and training metrics

#### 1.3 Network Architecture

| Layer Type     | Description               |
|----------------|---------------------------|
| Input Layer    | 784 neurons (28×28 pixels) |
| Hidden Layer 1 | 128 neurons               |
| Hidden Layer 2 | 64 neurons                |
| Hidden Layer 3 | 32 neurons                |
| Output Layer   | 10 neurons (for 10 classes) |

Other specifications:
- **Seed:** 210 (from Roll No.)
- **Bias:** 1
- **Batch Size:** 21 (from Year 2021)
- **Activation:** 
  - Hidden layers: `Sigmoid`
  - Output layer: `Softmax`
- **Loss Function:** Cross-Entropy

---

## 📊 2. Training the Neural Network

Training was conducted under three different data split configurations.

### 🔹 2.1 Train-Test Split 70:30

- Plotted:
  - Loss & accuracy per epoch (25 epochs)
  - Test accuracy
  - Confusion matrix

### 🔹 2.2 Train-Test Split 80:20

- Similar performance metrics and plots:
  - Accuracy & loss curves
  - Confusion matrix
  - Generalization assessment

### 🔹 2.3 Train-Test Split 90:10

- Final and best performing model with most training data
- Included all plots:
  - Loss/Accuracy curves
  - Test performance
  - Confusion matrix

---

## 🧮 2.4 Parameters Summary

- All **trainable** and **non-trainable** parameters were calculated and summarized.
- Refer to the attached text section (or code output) for exact values after training.

---

## 📈 Key Observations

- Higher training data (90:10) yielded better accuracy and generalization
- Sigmoid activation required careful learning rate selection
- Softmax with cross-entropy produced stable gradients
- Model performance visualized through curves and confusion matrix

---

## 🔗 Resources Used

- [GeeksforGeeks – Neural Networks](https://www.geeksforgeeks.org/neural-networks-a-beginners-guide/)
- [IBM Neural Network Guide](https://www.ibm.com/topics/neural-networks)
- [Wikipedia – Neural Networks](https://en.wikipedia.org/wiki/Neural_network)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/index.html)

---

## 👨‍🎓 Author Info

```text
Name       : Sahil Sharma
Program    : M.Sc - M.Tech (Mathematics & Data and Computational Sciences)
Institute  : Indian Institute of Technology, Jodhpur
