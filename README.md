# Skin-Cancer-Classifier

This is a deep learning-based Convolutional Neural Network (CNN) designed to analyze and classify dermoscopic images of pigmented lesions into several types of skin cancer in Python. Libraries including Pandas, PyTorch, NumPy, and TensorFlow were used to create this model. 

This project consists of a Convolutional Neural Network (CNN) designed to classify skin lesions into five categories: Actinic Keratosis (AK), Basal Cell Carcinoma (BCC), Benign Keratosis-like Lesions (BKL), Melanocytic Nevi (NV), and Melanoma (MEL). The CNN architecture includes four convolutional layers with increasing filter sizes, batch normalization, and adaptive average pooling, followed by a bottleneck layer and three fully connected layers. 

The HAM1000 dataset was used to train the model and the ISIC dataset was used to test the model. When running the code, both will be downloaded and sorted based on their true labels onto one's drive. Graphs to show the validation and loss per epoch can also be seen. 
