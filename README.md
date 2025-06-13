🛡️ Network Intrusion Detection using Supervised Machine Learning

This project is a GUI-based application built with Tkinter that applies Support Vector Machine (SVM) and Artificial Neural Networks (ANN) to detect network intrusions using the NSL-KDD dataset. It integrates feature selection techniques (like SelectKBest with chi-square) to improve model performance and provide real-time predictions on unseen data.

📌 Features

Upload and preprocess the NSL-KDD dataset

Remove non-numeric features and clean the data

Train SVM and ANN models with selected features

Display prediction results and accuracy metrics

Upload test samples and detect intrusions

Plot comparative accuracy of models

💽 GUI Overview

Built using tkinter, the interface provides:

File upload buttons

Step-by-step action flow

Text box displaying logs/results

Accuracy bar graph display

⚙️ Requirements

Install the required dependencies:

pip install -r requirements.txt

requirements.txt includes:

tkinter

imutils

matplotlib

numpy

pandas

scikit-learn

keras

tensorflow

🚀 Running the Application

python main.py

Then follow the steps in the GUI:

Upload dataset (NSL-KDD CSV)

Preprocess data

Generate model

Train using SVM / ANN

Upload test data to detect attacks

View accuracy graph

📂 Dataset

This project uses the NSL-KDD dataset, which can be downloaded from:
https://www.unb.ca/cic/datasets/nsl.html

Place the .csv file inside the project directory and load it via the GUI.

🧠 Algorithms Used

1. Support Vector Machine (SVM)

Kernel: RBF

Class weight: balanced

Feature selection: Chi-square test (SelectKBest)

2. Artificial Neural Network (ANN)

Input Layer: 25 features

Hidden Layers: 2

Output Layer: Binary (Normal/Anomaly)

Optimizer: Adam

Loss: Binary Crossentropy

📊 Output

Displays prediction logs in the GUI

Shows accuracy of both models

Visualizes comparison with a bar chart