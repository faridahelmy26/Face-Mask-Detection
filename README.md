# 🖥😷 Face Mask Detection using VGG16 + OpenCV

## 📌 Project Overview

This project is a **Face Mask Detection System** built with **Deep Learning** and **Computer Vision** techniques.
Using **VGG16 (Transfer Learning)**, the model is trained on the [Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset) to classify whether a person is wearing a mask or not.
The system also integrates with **OpenCV** for **real-time face detection**.

---

## ⚙️ Features

* ✅ Data preprocessing and augmentation with `ImageDataGenerator`
* ✅ Transfer Learning using **VGG16 (ImageNet weights)**
* ✅ Binary classification: `With Mask` 😷 vs. `Without Mask` 🚫
* ✅ Real-time face detection using Haar Cascades + OpenCV
* ✅ Model saved and reloaded for predictions

---

## 📊 Dataset

The dataset is available on Kaggle:
👉 [Face Mask Dataset] (https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)

* **Classes**: `with_mask`, `without_mask`
* Pre-split into **training (80%)** and **validation (20%)** using `split-folders`.

---

## 🧠 Model Architecture (Transfer Learning VGG16)

* Base: **VGG16** (ImageNet weights, frozen)
* Flatten + Dense(128, ReLU) + Dropout(0.5)
* Output: Dense(1, Sigmoid)

---

## 📈 Results

* High accuracy on validation set
* Real-time detection demo using OpenCV 🎥

Example:

```
😷 With Mask   → Green bounding box  
🚫 Without Mask → Red bounding box
```

---

## 🏷️ Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy, Matplotlib
* Kaggle API

---

## ✨ Author

👩‍💻 **Farida Helmy**

* GitHub: [faridahelmy26] (https://github.com/faridahelmy26)
* LinkedIn: [Farida Helmy] ([https://www.linkedin.com/in/faridahelmy26](https://www.linkedin.com/in/farida-helmy-0568302a3/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app))

---
