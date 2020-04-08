# PneumoniaDetection

Using Chest-X Ray images from a very well known Kaggle Dataset (https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia), we can use Deep Learning models to detect Pneumonia. 

## Motivation 

Healthcare is an important part of the current technological revolution, with more and more fields like Deep Learning applying methods to this versatile and pivotal field. Pneumonia is a very common infection with more than 10 million cases annually. Detecting this infection at an early stage using a simple chest x-ray scan could prove to be a game-changer.  

![Example Scans](https://i.imgur.com/jZqpV51.png)


## Technologies Used
This project uses Tensorflow 2.1.0 and Keras 2.3.0. The same code might not work with Tensorflow 1.x.x. 

## Environment Used
This project was executed in the Google Colab environment, with a GPU configuration. Each epoch during training took around 45 seconds, which may differ everytime. The Kaggle API was used to import the dataset into the Colab environment. 

## Architecture Used
This project used Transfer Learning techniques, with the base model being ResNet50 (https://keras.io/applications/#resnet), and the model has 50 layers. 

## Result
After a mere 10 epochs of training, the model gets an accuracy of __>80%__. Some small tweaks to the architecture should bring it above 90%. 

## Contribute 
Contributions are open from everyone. 
