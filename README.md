# 🧠 Brain Tumor MRI Detection Using Deep Learning 

A deep learning project that detects brain tumors from MRI images using Convolutional Neural Networks (CNNs).  
This project helps radiologists and researchers speed up tumor detection and assists in early diagnosis.

---

## 📸 Demo / Screenshot

![main.py](https://github.com/user-attachments/assets/6d14d1c5-71ea-4c74-a9ed-ac1a6135f913)
![web-interface](https://github.com/user-attachments/assets/145dabbe-713c-4647-9d1e-ebfbfd1ddc0d)
![output](https://github.com/user-attachments/assets/d5ece5e6-b7d8-4dc0-be83-1e134ca81219)

---

## ✨ Features
- 🏥 Detects presence of brain tumor from MRI scans.
- ⚡ Built using deep learning (CNN).
- 📊 Provides accuracy and loss graphs for model evaluation.
- 🔧 Easy-to-run training and inference scripts.

---

## 📊 Dataset

This project uses publicly available Brain MRI datasets, such as:
 
Download: https://www.kaggle.com/datasets/ahmedabuzar/brain-tumor-mri-data-set

---

## 📈 Trained Model

Trained model is also publicly available:

Download: https://www.kaggle.com/models/ahmedabuzar/brain-tumor-detection

---

## 📦 Installation

Clone the project and install dependencies:

```bash
git clone https://github.com/ahmad-abuzar/brain-mri-tumor-detection-using-deep-learning.git
```

Ensure Python 3.9 is Installed

```bash
python --version
```

Create a Virtual Enviroment

```bash
python -m venv myenv
```


Install Dependencies
```bash
pip install -r requirements.txt
```

Example requirements.txt for Python 3.9
```
tensorflow==2.14.0 
keras==2.14.0 
numpy 
pandas 
matplotlib 
seaborn 
scikit-learn 
```

Predict Using a New MRI Image
```
python main.py
```

---

## 📂 Project Structure

```
brain-tumor-detection/
├── dataset/
│   ├── Training/               # MRI images with tumor
│   ├── Testing/                # MRI images without tumor
├── models/
│   └── model.h5
├── Brain_Tumor_Detection.ipynb
├── main.py
├── requirements.txt
└── README.md
```

---


