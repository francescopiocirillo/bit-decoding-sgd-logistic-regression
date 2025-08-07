# 📶 Bit Decoding with Logistic Classification using SGD

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project implements a system for decoding binary sequences using **logistic regression** trained with **Stochastic Gradient Descent (SGD)**. It was developed as part of a university course project in Data Science (Master's Degree in Computer Engineering at University of Salerno), and showcases the design and evaluation of multiple binary classifiers in Python.

> Demonstrates proficiency in Python, logistic regression, stochastic optimization, and machine learning evaluation workflows.

---

## 📌 Objective

Given a set of 48 binary classification problems, each predicting a bit from a 2D feature vector, the objective is to:

1. Train 48 logistic regression models using **SGD with constant step-size**.
2. Analyze model performance to identify the most effective choice of parameters (especially learning rate).
3. Decode the binary sequence to reconstruct the original ASCII message hidden in the data.

---

## 🌍 Language Note

All code comments are written in Italian, as this project was originally developed in an academic setting in Italy. Nonetheless, the code structure, machine learning approach, and methodology follow international best practices.

The project brief is available both in English and Italian.

---

## 🛠️ Techniques Applied

- **Binary Logistic Regression** with 2D input
- **Stochastic Gradient Descent (SGD)** optimization
- **Binary classification across multiple problems (K=48)**
- **Confusion matrix** and classification error analysis
- **Bit decoding from ASCII binary sequence**

---

## 📈 Methodology Overview

- Each of the 48 classifiers is trained on a dedicated tranche of a shared dataset.
- Models are trained using constant step-size SGD, and multiple values of the step-size are tested.
- The algorithm tracks performance across iterations, allowing the selection of optimal weights β(i).
- The decoded output is evaluated for correctness against the target ASCII-encoded phrase.

---

## 📂 Repository Structure

```
📦 BIT-DECODING-SGD-LOGISTIC-CLASSIFICATION/
├── README.md
├── LICENSE
├── .gitignore
├── 📁 data/
│   └── homeworkclass.mat                      # Dataset MATLAB contenente dati per i 48 classificatori binari
├── 📁 instructions/
│   ├── project_description_logistic_classification_ENGLISH.pdf  # Descrizione del progetto in inglese
│   └── project_description_logistic_classification_ITALIAN.pdf  # Descrizione del progetto in italiano
└── 📁 notebooks/
    └── bit_decoding_logistic_classification.ipynb  # Notebook Jupyter con implementazione e analisi
```

---

## 🧪 Results

- A full logistic regression pipeline was implemented and tested successfully.
- Model performance is sensitive to the choice of step-size; analysis of training dynamics was used to select optimal weights.
- The decoded ASCII message confirms the classification pipeline was correctly implemented.

---

## 📊 Technologies Used

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Core Methods:** Logistic Regression, SGD
- **Libraries:** NumPy, Matplotlib

---

## 🎓 About the Project

This project was created as part of the *Data Science & Data Analysis* course (2024/2025) for the Master’s Degree in Computer Engineering at the **University of Salerno**.

## 👥 Team – University of Salerno
    
* [@francescopiocirillo](https://github.com/francescopiocirillo)
    
* [@alefaso-lucky](https://github.com/alefaso-lucky)

## 📬 Contacts

✉️ Got feedback or want to contribute? Feel free to open an Issue or submit a Pull Request!

## 📈 SEO Tags

```
logistic-regression, bit-decoding, binary-classification, stochastic-gradient-descent, machine-learning, jupyter-notebook, classification-metrics, python, data-science, ascii-decoding, supervised-learning, optimization, confusion-matrix
```

## 📄 License

This project is licensed under the **MIT License**, a permissive open-source license that allows anyone to use, modify, and distribute the software freely, as long as credit is given and the original license is included.

> In plain terms: **use it, build on it, just don’t blame us if something breaks**.

> ⭐ Like what you see? Consider giving the project a star!

