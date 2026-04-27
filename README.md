# 🥔 Potato Leaf Disease Detection using Image Classification (CNN)

## 📌 Project Overview

This project focuses on building a **Deep Learning image classification model** to detect potato plant diseases from leaf images using a **Convolutional Neural Network (CNN)**.

The model classifies potato leaf images into three categories:

* **Early Blight**
* **Late Blight**
* **Healthy**

The system can support **agricultural diagnostics** by enabling early detection of plant diseases, helping farmers take preventive actions and improve crop yield.

---

## 🎯 Project Objectives

* Understand image classification using deep learning
* Perform image preprocessing and data augmentation
* Build a Convolutional Neural Network (CNN)
* Train and validate the model using structured datasets
* Evaluate model performance using standard classification metrics

---

## 📂 Dataset Details

### Dataset Structure

The dataset is organized into three folders:

```text
Potato/
│
├── Train/
│     ├── Potato___Early_blight
│     ├── Potato___healthy
│     └── Potato___Late_blight
│
├── Valid/
│     ├── Potato___Early_blight
│     ├── Potato___healthy
│     └── Potato___Late_blight
│
├── Test/
│     ├── Potato___Early_blight
│     ├── Potato___healthy
│     └── Potato___Late_blight
```

### Classes

* Early Blight
* Late Blight
* Healthy

### Data Type

* Image dataset
* RGB leaf images
* High-resolution plant disease images

### Dataset Source

Kaggle Dataset:

https://www.kaggle.com/datasets/hafiznouman786/potato-plant-diseases-data

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 🧠 Model Architecture

The project uses a **Convolutional Neural Network (CNN)** consisting of:

* Convolutional Layers (feature extraction)
* Max Pooling Layers (dimension reduction)
* Flatten Layer
* Dense Layer
* Dropout Layer (to prevent overfitting)
* Output Layer (Softmax activation)

### Loss Function

Categorical Crossentropy

### Optimizer

Adam

### Evaluation Metric

Accuracy

---

## 🔄 Project Workflow

### 1. Data Understanding

* Load dataset
* Explore dataset structure
* Visualize sample images
* Identify class distribution

### 2. Data Preprocessing

* Resize images to 128 × 128
* Normalize pixel values (0–1 range)
* Apply data augmentation:

  * Rotation
  * Zoom
  * Horizontal flip

### 3. Model Building

* Build CNN model using TensorFlow/Keras
* Define architecture
* Compile model

### 4. Model Training

* Train model using training dataset
* Validate performance using validation dataset
* Monitor accuracy and loss

### 5. Model Evaluation

* Evaluate model using test dataset
* Generate confusion matrix
* Generate classification report

---

## 📊 Model Evaluation Metrics

The model performance is evaluated using:

* **Accuracy**
* **Confusion Matrix**
* **Precision**
* **Recall**
* **F1-Score**
* **Classification Report**

Example:

```text
Test Accuracy: 94%

Confusion Matrix:
[[50  2  1]
 [ 3 47  0]
 [ 1  2 49]]
```

---

## 📁 Project Structure

```text
Potato-Leaf-Disease-Detection
│
├── Train/
├── Valid/
├── Test/
│
├── potato_disease_classification.ipynb
├── potato_disease_model.h5
├── README.md
├── requirements.txt
```

---

## ▶️ How to Run the Project

### Step 1 — Install Required Libraries

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn
```

### Step 2 — Upload Dataset

Upload the dataset ZIP file to Google Colab or place the dataset folders in your project directory.

### Step 3 — Run the Notebook

Open:

```text
potato_disease_classification.ipynb
```

Then run all cells sequentially.

---

## 📈 Results

* The CNN model successfully classifies potato leaf diseases
* Training and validation accuracy improved across epochs
* The model achieved high classification performance on test data

---

## 💡 Key Learnings

* Image preprocessing and augmentation
* Convolutional Neural Network design
* Deep learning model training and validation
* Model evaluation using classification metrics
* Practical implementation of computer vision

---

## 🚀 Future Improvements

* Use Transfer Learning (MobileNet, ResNet, VGG16)
* Increase dataset size
* Deploy model using Streamlit
* Build real-time disease detection system
* Develop mobile application for farmers

---

## 👩‍💻 Author

**Sahana**
AI & Data Science Student

---

## ⭐ If you found this project useful

Please consider giving this repository a **star ⭐**
