🦠 Malaria Cell Classification Using Deep Learning

This project implements a deep-learning model to classify malaria-infected and uninfected cells from microscopic blood smear images.
Using a Convolutional Neural Network (CNN), the model automates malaria detection — reducing manual workload and improving accuracy.

📌 Project Overview

Traditional malaria diagnosis requires manual inspection of blood smear slides, which is both slow and prone to human error.
This project uses deep learning to automate the classification process using labeled images of parasitized and uninfected cells.

The main notebook used in this project:

malariacell_model.ipynb

✨ Features

🧬 CNN-based image classification

🖼️ Preprocessing and data augmentation

📈 Visualization of training accuracy and loss

🔍 Binary prediction: Infected vs. Uninfected

🧩 Easily extendable to new datasets or architectures

📂 Dataset

This project uses the NIH Malaria Dataset, containing 27,000+ labeled cell images.

🔗 Dataset link:
https://lhncbc.nlm.nih.gov/LHC-publications/pubs/MalariaDataset

🧠 Model Architecture

The CNN consists of:

Conv2D

MaxPooling2D

Dropout

Dense layers

Softmax output layer

Training configuration:

Optimizer: Adam

Loss Function: Categorical Crossentropy

Evaluation Metric: Accuracy

📊 Results

The model demonstrates strong performance for binary malaria cell classification.
Training and validation plots (accuracy & loss) are shown in the notebook.
