Emotion Detection Using Images
This project is focused on detecting human emotions from images using a Convolutional Neural Network (CNN). The model is trained to classify images into one of seven emotions: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

Language and Libraries
Programming Language:
Python 3.7 or above


Required Libraries:

TensorFlow 2.x
Keras
NumPy
Matplotlib
Seaborn
OpenCV
Scikit-learn
Tqdm

You can install the required libraries using the following command:

pip install tensorflow keras numpy matplotlib seaborn opencv-python scikit-learn tqdm
Project Structure
Emotion Detection using images dataset_momna.ipynb: The main notebook containing all code for loading the dataset, building the model, training, and evaluation.
train/: Directory containing training images for the model.
Dataset
The dataset used for this project includes grayscale images categorized into seven emotion classes. The images are resized to 50x50 pixels for training and testing.

Model Architecture
The CNN model is built using Keras with TensorFlow as the backend. It includes:

Convolutional layers
Batch Normalization layers
Max-Pooling layers
Dropout layers
Dense layers with softmax activation for classification
Training
The model is trained for 30 epochs with 10% of the data reserved for validation. The training process is monitored using accuracy and loss metrics.

Evaluation
After training, the model's performance is evaluated using a confusion matrix and a classification report, highlighting the precision, recall, and F1-score for each emotion category.

How to Run

Clone this repository:
git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection
Install the required libraries:

pip install -r requirements.txt
Run the notebook or script to train and evaluate the model:

jupyter notebook Emotion Detection using images dataset_momna.ipynb
Results
The model achieved an accuracy of approximately 55%, with the highest performance in detecting the "Happy" and "Surprise" emotions.