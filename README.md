Cataract_Classification_Public
# Developed Mobile Application using Deep learning for Cataract classification. 

# This project presents a mobile application for cataract detection and classification using deep learning techniques. Cataracts are a leading cause of vision loss worldwide, and early detection can significantly reduce the risk of blindness. Our solution leverages Convolutional Neural Networks (CNNs) with transfer learning models to classify eye images as Normal or Cataract.

🔍 Key Features

Deep Learning Models:

VGG19 for fundus image classification

Inception V3 for digital image classification

High Accuracy Performance:

Fundus Images → 96% accuracy

Digital Images → 97% accuracy

Mobile Application Integration:

Implemented using TensorFlow Lite and Android Studio

Users can capture or upload eye images for real-time classification

Firebase integration for user authentication and data storage

📂 Dataset

Fundus images sourced from the Ocular Disease Intelligent Recognition (ODIR) dataset

Digital eye images collected from open-source repositories

Preprocessing performed using OpenCV, NumPy, and Pandas

⚙️ Tools & Technologies

Python, TensorFlow, Keras, Scikit-learn for model training

Google Colab for experimentation and evaluation

Android Studio (Java/XML) for mobile application development

Firebase for cloud storage and user verification

📊 Results

Fundus image classification: 96% accuracy, F1-score 0.96

Digital image classification: 97% accuracy, F1-score 0.97

Optimized models converted to TensorFlow Lite for mobile deployment

🚀 Future Improvements

Extend detection to other eye diseases (Glaucoma, Diabetic Retinopathy, etc.)

Implement severity grading of cataracts (mild, moderate, severe)

Telemedicine integration for remote diagnosis and consultation
