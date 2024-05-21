**Digital Image Forgery Detection Using Transfer Learning**

The project leverages the power of transfer learning to identify forged images within a dataset of 12,614 labeled images.

**Dataset **

https://www.kaggle.com/datasets/nishaahin/casiav2revised


**Overview**

The primary goal of this project is to compare the effectiveness of machine learning, ensemble learning, and transfer learning models in detecting digital image forgeries. The project involves several key steps:

**Preprocessing Techniques:**

**Error Level Analysis (ELA):** Used to identify potential forged areas by comparing compression levels across different parts of the image.
**Statistical Residual Model (SRM):** A denoising technique that enhances patterns and areas that may be forged.
**Principal Component Analysis (PCA):** Applied for dimensionality reduction while retaining the most important features.

**Model Implementation:**

**Machine Learning Models:** Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Naive Bayes, and Decision Tree.

**Ensemble Models:** Random Forest and AdaBoost.

**Transfer Learning Models:** VGG16, VGG19, DenseNet121, and MobileNetV2.

**Results**

Through rigorous experimentation, we found that transfer learning models significantly outperformed traditional machine learning and ensemble models. Among the models tested, DenseNet121 achieved the highest accuracy of 92%, demonstrating its superior capability in the task of digital image forgery detection.
