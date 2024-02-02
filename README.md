# Breast-Cancer-Prediction-CNN
This project aims to develop an End-End Convolutional Neural Network (CNN) model for predicting the presence of breast cancer in mammogram images. Early and accurate detection is crucial for successful treatment and improving patient outcomes.
# Project Workflow
1) download dataset from kaggle: https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset
2) Importing our dependencies, data preprocessing and data Augmentation
3) Build our CNN model
4) Build and deploy a streamlit web application to outputs a prediction of whether the image is likely to be benign (non-cancerous) or malignant (cancerous) and normal.
5) Build our Docker file

# WHY THIS PROJECT
1) Breast cancer is a common and potentially life-threatening disease, so early detection significantly improves survival rates.
2) CNNs excel at recognizing patterns in images, making them suitable for cancer detection tasks.
3) This project has the potential to aid doctors in identifying suspicious lesions and expedite diagnosis.

# PROJECT FOLDERS AND FILES EXPLAINED
TEST IMAGES: contain sample of images that can be used to test our streamlit web app

APP/TRAINED_MODELS: contain our model. you can download from this link:

APP/DOCERFILE: This contains all the command  or instruction in order to build the Docker image

APP/Class_indices.json: contains the classes of normal, bengin, maligan

APP/config.toml, credentials.toml: This are default files streamlit needs

APP/MAIN.PY: This python scripts is used to write our streamlit code

APP/requirements.txt: contains list of libraries and dependecies needed to run our web application.

MODEL_NOTEBOOK: This contain our .ipynb file that was used to train our dataset and perform data preprocessing and data augmentation.

# How to run this project
1) clone the repository
2) Enter project Directory
3) Build the Docker image, make sure you have docker running
4) open a terminal and run streamlit run app/main.py
 
NOTE: This project is for educational and research purposes only,for questions and collaboration reach out to me via email igbokwewinnie@gmail.com

Project still in development phase: others things that can be done Deploying on Cloud service


