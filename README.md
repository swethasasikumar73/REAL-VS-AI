# Real vs AI-Generated Image Detection using CNN

## 📌 Project Overview

This project uses a **Convolutional Neural Network (CNN)** to classify images as either **Real** or **AI-Generated**.

The model learns visual patterns from images and predicts whether a given image belongs to the real-image class or the AI-generated-image class.

## 🎯 Objective

The main objective of this project is to develop an image classification model capable of distinguishing between real photographs and AI-generated images using deep learning techniques.

## 📊 Dataset

* **Dataset Size:** 1,000 images
* **Classes:**

  * Real Images
  * AI-Generated Images
* Images were organized into separate folders based on their class labels.
* The dataset was used for model training and evaluation.

## 🧠 Model

A **Convolutional Neural Network (CNN)** was used for image classification.

The CNN learns important visual features such as:

* Edges and textures
* Shapes and patterns
* Image-level visual characteristics

These learned features are then used to classify an image as **Real** or **AI-Generated**.

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* Convolutional Neural Network (CNN)
* NumPy
* Pandas
* Matplotlib
* Google Colab
* Jupyter Notebook

## 🔄 Project Workflow

```text
Dataset
   ↓
Image Loading
   ↓
Data Preprocessing
   ↓
Train / Validation Split
   ↓
CNN Model
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Real / AI-Generated Prediction
```

## ⚙️ Image Preprocessing

The images were prepared before training by:

1. Resizing images to a consistent input size.
2. Normalizing pixel values.
3. Assigning class labels.
4. Splitting the dataset into training and validation sets.

## 📈 Model Training

The CNN model was trained using the prepared image dataset. During training, the model learned distinguishing visual features between real and AI-generated images.

The model performance was evaluated using validation data to understand its classification capability.

## 🔍 Prediction

After training, the model can accept a new image and predict whether it is:

**Real Image** or **AI-Generated Image**

## 🚀 Future Improvements

* Increase the size and diversity of the dataset.
* Use transfer learning models such as ResNet, EfficientNet or MobileNet.
* Apply data augmentation to improve generalization.
* Add precision, recall and F1-score evaluation.
* Deploy the model as a web application.
* Improve detection of high-quality AI-generated images.

## 👩‍💻 Author

**Swetha Sasikumar**

M.Sc. Computer Science
PSGR Krishnammal College for Women, Coimbatore

## ⭐ Project Highlights

* CNN-based image classification
* Real vs AI-generated image detection
* 1,000-image dataset
* Image preprocessing and model training
* Deep learning-based classification
