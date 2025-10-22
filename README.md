# 🧠 AI Tools and Frameworks Assignment

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?logo=googlecolab&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success)


## 👥 Group Members
1. [George Omondi Alando-Group Leader]
2. [Maureen Gathoni]
3. [Francis Promise]
4. [Bill Clinton Onyango]
5. [Erick Midida]
6. [Abraham Sitori]

---

## 📘 Project Overview
This repository contains our group work for the **AI Tools and Frameworks Assignment**, covering three core areas:  
**Theoretical Understanding**, **Practical Implementation**, and **Ethics & Optimization**.  
The work demonstrates our ability to apply machine learning frameworks — **TensorFlow**, **PyTorch**, **Scikit-learn**, and **spaCy** — in solving real-world problems through both theory and implementation.

---

## 🧩 Part 1: Theoretical Understanding
This section covers short conceptual questions on:
- Differences between **TensorFlow** and **PyTorch**.
- Use cases of **Jupyter Notebooks** in AI workflows.
- How **spaCy** enhances NLP tasks beyond raw Python text handling.  
Additionally, we provide a brief comparative analysis between **Scikit-learn** and **TensorFlow** focusing on:
- Target applications (classical ML vs deep learning)
- Ease of use for beginners
- Community support

---

## ⚙️ Part 2: Practical Implementation

### 🪴 Task 1: Classical ML with Scikit-learn
- **Dataset:** Iris Species  
- **Goal:** Train a Decision Tree classifier to predict species.  
- **Deliverable:** Jupyter Notebook with preprocessing, training, and evaluation (accuracy, precision, recall).  

### 🧮 Task 2: Deep Learning with TensorFlow/PyTorch
- **Dataset:** MNIST Handwritten Digits  
- **Goal:** Build a CNN model for digit classification achieving >95% test accuracy.  
- **Deliverable:** Model training script with architecture, evaluation metrics, and sample visualizations.

### 💬 Task 3: NLP with spaCy
- **Dataset:** Amazon Product Reviews  
- **Goal:** Extract product and brand entities via NER; analyze sentiment using rule-based approach (TextBlob).  
- **Deliverable:** Notebook showing code snippets, extracted entities, and sentiment summary chart.

---

## 🧭 Part 3: Ethics & Optimization

### 🔍 Ethical Considerations
AI systems, while powerful, are not immune to bias. Our MNIST and Amazon Review models illustrate this in different ways:

- **MNIST (Image Data):**  
  Bias may emerge from uneven class distribution or overfitting to digit styles written by specific demographics (e.g., certain handwriting types).  
  *Mitigation:* Applying **TensorFlow Fairness Indicators** can monitor model performance across subgroups to ensure equitable accuracy. Data augmentation and class balancing also help reduce bias propagation.

- **Amazon Reviews (Text Data):**  
  Sentiment analysis models may misinterpret linguistic nuances or sarcasm, leading to skewed sentiment toward certain product categories or cultural expressions.  
  *Mitigation:* Using **spaCy’s rule-based patterns** to complement statistical models improves interpretability and helps correct contextual errors. Incorporating diverse linguistic datasets further minimizes this bias.

Ethical AI demands continuous model auditing, documentation of assumptions, and transparency in deployment decisions. Fairness tools and human oversight remain essential to ensure that models serve users responsibly and inclusively.

---

### 🧰 Troubleshooting & Optimization
During implementation, we encountered and resolved common errors such as:
- TensorFlow **dimension mismatches** in CNN layers.
- Misaligned **label encodings** during preprocessing.
- Incorrect or incompatible **loss functions** for classification tasks.  

Optimization included using appropriate activation functions, normalizing input data, and validating model performance across multiple runs.

---


