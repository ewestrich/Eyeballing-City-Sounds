# Eyeballing-City-Sounds
Built a Convolutional Neural Networks to Classify Sound Types with Spectogram images

## Overview
- Through representing audio recording as spectogram images, were able to classify audio sounds with an image based Machine Learning image model. Classification of audio data itself can be complex to interpret and use a machine learning model to classify. Through transforming the audio into an image, we could then utilize an image based Deep Learning technique to build a classification model.

## Business Understanding
- Image detection is a very common use case of Machine Learning modeling. For example, self driving cars can detect what type of object is nearby or what color a traffic light is. Sound detection and classicification is less available but no less useful. Applications of audio detection using a classification model to interpret surrounding sounds would be assisting an individual who is hard of hearing in being more aware of their surroundings such as alerting them of a dog barking or even a distant gun shot.

## Data Understanding and Preperation
- The data is sourced from [UrbanSounds8K](https://urbansounddataset.weebly.com/urbansound8k.html) with 8,700 recording of 10 different sound classes (Dog Barking, Car Horn, Jackhammer, Street Music etc.)
- Audio recording were loaded into a Jupyter Notebook using the package Librosa and analysed
- Through a custom function, each audio file was transformed and stored locally as Mel Spectogram png image
  
  
## Modeling
- Split the data in training and testing data.


## Model Evaluation
- Model performed at 81% accuracy on test data set
![CNN_Model_Confusion-Matrix](https://github.com/ewestrich/Eyeballing-City-Sounds/assets/129399785/987537cf-46fc-4851-b0b8-d14dacd0eb2c)
- Evaluted model on several sounds recorded out in the street and saw success there as well
  
## Uses and Next Steps
- Utilize a dashboard to test newly recorded sounds and see how well the model does
- Implement in a smart phone app to alert those who are hard of hearing of sounds in their surroundings










