# GANs_Generate_Realistic_Celebrity_Images_ML
Generative Adversarial Networks (GANs) to Image Generater

This project demonstrates a full-stack machine learning application using Generative Adversarial Networks (GANs) to generate images. The model is trained using the CelebA dataset and deployed as a web application using Flask.

## Project Structure

```plaintext
gan-image-generator/
│
├── app.py
├── requirements.txt
├── Procfile
├── README.md
├── static/
│   ├── style.css
│   └── script.js
├── templates/
│   └── index.html
└── preprocess.py

## Component

Data Collection and Preprocessing: Utilize the CelebA dataset for training. Preprocess the images to a uniform size and scale.

GAN Model Training: Train a Deep Convolutional GAN (DCGAN) using TensorFlow and Keras.

Model Saving: Save the trained generator model for deployment.

Backend Development (Flask): Create a Flask application to serve the GAN model.

Frontend Development (HTML/CSS/JavaScript): Develop a user interface for interacting with the GAN model.

Deployment: Deploy the Flask application on a cloud platform like Heroku.
