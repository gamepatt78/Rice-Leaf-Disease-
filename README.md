Rice Leaf Disease Detection
📌 Project Overview

Rice Leaf Disease Detection is a machine learning and deep learning project designed to identify diseases affecting rice plants from leaf images.

The system uses image processing and an image-classification model to analyze a rice leaf image and predict the disease category represented in the training dataset.

This project aims to support early identification of rice leaf diseases and demonstrate the use of artificial intelligence in agriculture.

🎯 Objectives

Detect diseases from rice leaf images.

Preprocess and analyze plant images.

Train a deep learning image-classification model.

Evaluate the performance of the trained model.

Provide predictions through a simple application.

Demonstrate the application of computer vision in agriculture.

📁 Project Structure
Rice-Leaf-Disease/
├── dataset/
├── models/
├── src/
├── app.py
├── requirements.txt
└── README.md

Folder Description

dataset/ — Contains rice leaf images used for training and testing.

models/ — Stores the trained machine learning/deep learning model.

src/ — Contains preprocessing, training, and prediction code.

app.py — Runs the user interface.

requirements.txt — Contains the required Python packages.

README.md — Project documentation.

🛠️ Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy

Pandas

Matplotlib

Scikit-learn

Pillow

Streamlit

📊 Dataset

The dataset contains images of healthy and diseased rice leaves.

A possible dataset structure is:

dataset/
├── train/
│   ├── healthy/
│   ├── bacterial_leaf_blight/
│   ├── brown_spot/
│   └── leaf_smut/
│
├── validation/
│   ├── healthy/
│   ├── bacterial_leaf_blight/
│   ├── brown_spot/
│   └── leaf_smut/
│
└── test/
    ├── healthy/
    ├── bacterial_leaf_blight/
    ├── brown_spot/
    └── leaf_smut/


The actual class names should match the dataset used by the project.

🧠 Machine Learning Workflow
Rice Leaf Image
       ↓
Image Preprocessing
       ↓
Image Resizing
       ↓
Normalization
       ↓
Data Augmentation
       ↓
Deep Learning Model
       ↓
Disease Classification
       ↓
Predicted Disease

⚙️ Installation
1. Clone the repository
git clone <repository-url>

2. Open the project directory
cd Rice-Leaf-Disease

3. Create a virtual environment
python -m venv venv

4. Activate the virtual environment

Windows:

venv\Scripts\activate


Linux/macOS:

source venv/bin/activate

5. Install dependencies
pip install -r requirements.txt

📦 Requirements

Example requirements.txt:

tensorflow
numpy
pandas
opencv-python
matplotlib
scikit-learn
pillow
streamlit

🏋️ Train the Model

Run the training script:

python src/train.py


After training, save the model in the models/ directory.

Example:

models/
└── rice_leaf_disease_model.h5

🔍 Prediction

Run the prediction script:

python src/predict.py


The system will process the input rice leaf image and predict the corresponding disease category.

🖥️ Run the Application

If the project uses Streamlit:

streamlit run app.py


The application allows the user to upload a rice leaf image and receive the model's prediction.

Example workflow:

Upload Rice Leaf Image
          ↓
   Image Preprocessing
          ↓
    Trained Model
          ↓
   Disease Prediction
          ↓
    Display Result

📈 Model Evaluation

The model can be evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Example:

Accuracy  : XX%
Precision : XX%
Recall    : XX%
F1-Score  : XX%


Replace these values with the actual results obtained during model evaluation.

⚠️ Limitations

Model performance depends on the quality of the dataset.

Poor-quality images may reduce prediction accuracy.

Different lighting conditions can affect image classification.

The model may not recognize diseases that were not included in the training dataset.

Predictions should be validated by agricultural experts before making treatment decisions.

🚀 Future Improvements

Add more rice disease categories.

Increase dataset size and image diversity.

Use transfer-learning models such as MobileNet, ResNet, or EfficientNet.

Improve image preprocessing and augmentation.

Add disease treatment and prevention information.

Develop a mobile application.

Deploy the model as a web service.

Test the model on real-world field images.

🤝 Contributing

Contributions are welcome.

Fork the repository.

Create a new branch.

Make your changes.

Test the changes.

Commit your changes.

Create a pull request.

🌾 Project Applications

This project can be used as an educational example of how computer vision and deep learning can assist with:

Crop disease identification.

Agricultural image classification.

Plant health monitoring.

Smart farming applications.

Early disease detection.

📄 License

This project is intended for educational and research purposes. Add an appropriate open-source license before distributing the project publicly.

👨‍💻 Author

Your Name

GitHub: <your-github-profile>

Email: <your-email>
