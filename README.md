📌 Introduction

Malaria is one of the most dangerous infectious diseases caused by parasites transmitted through mosquito bites. Early detection and treatment are very important to save lives.

This project uses Deep Learning and Convolutional Neural Networks (CNN) to detect whether a blood cell image is infected with malaria or not. The system analyzes microscopic cell images and classifies them into:

Parasitized
Uninfected

The application helps automate malaria diagnosis with high accuracy and reduces manual effort in laboratories.

🎯 Project Objective

The main objective of this project is to:

Detect malaria-infected blood cells automatically
Reduce human error in diagnosis
Provide faster medical analysis
Improve healthcare support using Artificial Intelligence

This system can be useful in hospitals, laboratories, and healthcare centers for quick malaria screening.

🧠 Deep Learning Model

The project uses a Convolutional Neural Network (CNN) model for image classification.

Workflow:
Load Cell Images
Preprocess Dataset
Train CNN Model
Test Model Accuracy
Predict Malaria Infection
Display Results
🏁 Technology Stack
Technology	Purpose
Python	Programming Language
TensorFlow / Keras	Deep Learning Framework
OpenCV	Image Processing
NumPy	Numerical Operations
Pandas	Data Handling
Matplotlib	Visualization
Flask	Web Application Framework
HTML/CSS/Bootstrap	Frontend Development
📂 Dataset

The dataset contains microscopic images of malaria-infected and uninfected blood cells.

Classes:
Parasitized
Uninfected

Dataset Source:
NIH Malaria Dataset

📁 Project Structure
Malaria-Detection-Using-Deep-Learning/
│
├── static/
├── templates/
├── dataset/
├── models/
├── app.py
├── train_model.py
├── predict.py
├── requirements.txt
└── README.md


⚙️ Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/your-username/Malaria-Detection-Using-Deep-Learning.git
2️⃣ Move to Project Directory
cd Malaria-Detection-Using-Deep-Learning
3️⃣ Install Required Libraries
pip install -r requirements.txt
▶️ Run the Project
Train the Model
python train_model.py
Start the Flask Application
python app.py

🌐 Open in Browser
http://127.0.0.1:5000/

📊 Features
✅ Malaria Cell Detection
✅ Deep Learning Based Prediction
✅ Image Upload Support
✅ High Accuracy Classification
✅ User-Friendly Interface
✅ Fast Prediction System

📈 Output
The system predicts whether the uploaded blood cell image is:

Parasitized
Uninfected

It also displays model accuracy and prediction results.

🚀 Future Enhancements
Improve model accuracy using advanced CNN architectures
Deploy application on cloud platforms
Add real-time camera scanning support
Integrate with hospital management systems
Mobile application development


👨‍💻 Author
Vaijanth
