# MNIST Handwritten Digit Recognizer

A complete deep learning computer vision pipeline designed to recognize and classify handwritten digits (0-9). This project features a Convolutional Neural Network (CNN) built and trained from scratch using TensorFlow and Keras.

## 🚀 Features
* **Model Training:** A fully configured CNN trained on the 70,000-image MNIST dataset, achieving >97% accuracy.
* **Custom Inference:** Includes a testing suite to process and predict custom, hand-drawn images.
* **Data Exploration:** Custom scripts to extract, visualize, and organize the raw MNIST data arrays into human-readable .png files.
* **Interactive Learning:** Built using Jupyter Notebooks with step-by-step human-readable documentation explaining the mathematics and code behind the AI.

## 📁 Project Structure
* train.ipynb / train.py: The core script that loads data, builds the CNN, trains the model, and saves the output (mnist_model.keras).
* predict.ipynb: An inference script that formats and tests custom user-drawn images (e.g., my_digit.png).
* explore_mnist.ipynb: A data visualization tool to sample the training dataset.
* download_all_mnist.ipynb: A script to extract the entire dataset of 70,000 images into categorized folders.
* requirements.txt: All necessary Python dependencies.

## 🛠️ Installation & Setup
To run this project locally, clone the repository and set up a virtual environment:

Step 1. Clone the repository:
git clone https://github.com/umandathathsarani/mnist-digit-recognizer.git
cd mnist-digit-recognizer

Step 2. Create and activate a virtual environment:
python -m venv .venv
.\.venv\Scripts\Activate.ps1

Step 3. Install dependencies:
pip install -r requirements.txt

## ⚖️ License
All Rights Reserved. See the LICENSE.md file for details. No permission is granted to copy, distribute, or modify this code without explicit consent.