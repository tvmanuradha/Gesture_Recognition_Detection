# Gesture Recognition

   

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

## Problem Statement
   Imagine working as a data scientist at a home electronics company which manufactures state of the art smart televisions. 
   We need to develop a smart feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 
   The gestures are continuously monitored by the webcam mounted on the TV.
   Each gesture corresponds to a specific command:

	Thumbs up: Increase the volume
	Thumbs down: Decrease the volume
	Left swipe: 'Jump' backwards 10 seconds
	Right swipe: 'Jump' forward 10 seconds
	Stop: Pause the movie
	
	Need to build a build different model to test which model gives better result. 


  Goal:-   
	Generator: 
	The generator should be able to take a batch of videos as input without any error. 
	Steps like cropping, resizing and normalization should be performed successfully.

	Model: 
	Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved.

	
## Approach
	Different approaches has been used to build the model and it's listed below.
	Simple Conv3D Model
	Conv3D with Batch Normalization
	Conv3D , Batch Normalization and Dropout
	Conv2D with LSTM
	Conv2D with GRU
	Transfer Learning (VGG16) with LSTM Model
	VGG16 + GRU
	TransferLearning(Mobilenet) + GRU Model



## Conclusions

  1. The model has achieved maximum train and validation  accuracy of 97.08% and 90.83% respectively using Transfer Learning using Mobilenet anf GRU.
     
    
    
    
## Technologies Used

    - pandas - version 1.2.4
	- numpy - version 1.20.1
	- seaborn - version 0.11.1
	- matplotlib - version 3.3.4
	- python - version 3.6.3
	- statsmodels.api - version 0.12.2
	- sklearn - version 0.24.1
    - Tensorflow version 2.8.0
    - Keras version 2.8.0
    
## Acknowledgements

    This project would not have been possible without UpGrad lectures and mentors support
        

## Contact
    Created by [anuradha.vijayakumar@gmail.com & krishnachitrak@gmail.com] - feel free to contact me!
	

