# Facial-Expression-Recognition-with-keras

## About Project
The project can be downloaded from [download the project from here]( https://drive.google.com/file/d/1ILPjHd2QlKYRbnguwzga0GiAl6F3osv_/view?usp=sharing). 
The project is about recognizing facial expressions and classifying them among the 7 universal expressions which are Angry, Happy, Neutral, Surprise, Disgust, Sad and Fear.
The dataset used in this project was collected in 2013 for KAGGLE and ICI machine learning competition to recognize facial expressions.The dataset consists of 48x48 pixels gray scale images of faces. The dataset contains 7 universal expressions. They are: 
-	Angry
-	Happy
-	Neutral
-	Surprise
-	Disgust
-	Sad
-	Fear

The project comprises of:
- Develop a facial expression recognition model in Keras
- Build and train a convolutional neural network (CNN)
- Deploy the trained model to a web interface with Flask
- Apply the model to real-time video streams and image data

In this project, the CNN model architecture has four convolution layers and 2 dense(fully connected) layers after this the model is flattened. The optimizer used is adam. The loss function is categorical_crossentropy and activation function is softmax. After training the model with 15 epocs the accuracy achieved is around 63%. The accuracy can be improved by balancing the dataset with augmentation and tuning the hyperparameters of model.

## Instructions to run the project
This .zip file contains all the code and data used in the project. It includes the FER 2013 dataset, completed Jupyter notebook for training, the Flask app to serve predictions, and other utility scripts. Please feel free to modify any and all aspects of the code to suit your needs.

Once you have downloaded and extracted Project.zip, make sure to install dependencies using pipenv with the provided Pipfile and execute all commands using pipenv. Also, please make sure to add the correct path to the video file in camera.py on line 11. Next, to install pipenv, the dependencies, and run the main.py file, execute the following commands from your terminal or command prompt, making sure to add the right paths where necessary:

- cd \path\to\Project\
- pip install pipenv
- pipenv install
- pipenv run python3 main.py

you can test the project from your own webcam by just changing one line of code. Instead of providing path of video in camera.py on line 11 just provide 0 without braces. It will automatically detect your default camera. 


