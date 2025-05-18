**🧠 Brain Tumor Detection using CNN**
This project demonstrates a deep learning-based approach to detect brain tumors from MRI images using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

**📌 Project Overview**
This project focuses on classifying MRI images into two categories:

No Tumor

Yes Tumor

A custom CNN model is trained on labeled MRI data to detect the presence of tumors in the brain with high accuracy.

**🗂️ Dataset**
The dataset used in this project contains MRI brain scan images and is organized into two folders:

yes/: Images with brain tumors.

no/: Images without brain tumors.

The dataset was downloaded from Kaggle and is locally stored in the project directory.

**🧠 Model Architecture**
The CNN architecture includes:

Multiple Conv2D layers with ReLU activation

MaxPooling2D layers to reduce spatial dimensions

Flatten and Dense layers for classification

Dropout layer to prevent overfitting

Sigmoid activation for binary classification

✅ Results
**Test Accuracy: ~95.5%**

**Loss: ~0.27 after 5 epochs**

Evaluation Metric: Categorical Crossentropy Loss and Accuracy

**📈 Libraries Used**
Python
TensorFlow / Keras
NumPy
OpenCV
Pillow (PIL)
Sklearn

**💡 Features**
Image preprocessing with OpenCV and PIL

Custom CNN architecture without pre-trained models

Data splitting and normalization

Visualization of training performance

Easy-to-understand implementation for beginners

**🚀 Future Improvements**
Add data augmentation for better generalization

Implement model using transfer learning (e.g., VGG16, ResNet)

Deploy as a web app using Streamlit or Flask

**📌 Author**
**Name :** Muhammad Hamza Awan
**Linkedin Link** : https://www.linkedin.com/in/muhammad-hamza-b83748241/
