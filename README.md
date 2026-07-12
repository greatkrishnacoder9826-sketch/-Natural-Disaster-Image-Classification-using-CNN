# 🌍 Natural Disaster Image Classification using CNN

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to classify images of different natural disasters.

The model is trained on a custom image dataset and learns visual patterns to identify disaster categories automatically.

## 🎯 Objective

The main goal of this project is to build an image classification model capable of recognizing different types of natural disasters from images using Deep Learning.

---

## 🖼️ Dataset

The dataset contains images organized into separate folders.

Example structure:

```
Cyclone_Wildfire_Flood_Earthquake_Dataset/
│
├── Cyclone/
├── Earthquake/
├── Flood/
└── Wildfire/
```

Each folder represents one class.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📚 Workflow

1. Load image dataset
2. Data preprocessing
3. Image normalization
4. Train-validation split
5. CNN model creation
6. Model training
7. Performance evaluation
8. Prediction on unseen images

---

## 🧠 CNN Architecture

The model consists of:

- Image Input Layer
- Rescaling Layer
- Convolution Layers
- MaxPooling Layers
- Flatten Layer
- Dense Layers
- Output Layer (Softmax)

---

## 🚀 Model Training

The model is trained using TensorFlow's `image_dataset_from_directory()` API.

### Image Size

```
224 × 224
```

### Normalization

Images are rescaled between **0 and 1** before training.

---

## 📊 Evaluation Metrics

The project evaluates the model using:

- Accuracy
- Loss
- Validation Accuracy
- Validation Loss

---

## 📂 Project Structure

```
Natural-Disaster-CNN/
│
├── Dataset/
│
├── Natural_Disaster_CNN.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Natural-Disaster-CNN.git
```

Move inside project

```bash
cd Natural-Disaster-CNN
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
tensorflow
numpy
pandas
matplotlib
scikit-learn
```

---

## 📈 Future Improvements

- Increase dataset size
- Apply Data Augmentation
- Use Transfer Learning (ResNet50, EfficientNet)
- Hyperparameter tuning
- Deploy using Streamlit
- Build a Flask/FastAPI API
- Convert model to TensorFlow Lite

---

## 💡 Applications

- Disaster Monitoring
- Emergency Response
- Satellite Image Analysis
- Smart Warning Systems
- AI-powered Disaster Detection

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub.

---

## 👨‍💻 Author

**Krishna Great**

GitHub: https://github.com/greatkrishnacoder9826-sketch

---

## 📄 License

This project is licensed under the MIT License.
