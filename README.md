# Machine-Learning-Engineer-Nano-degree-Udacity
This repo contains all the projects files which are implemented as part of Machine learning engineer Nanodegree which is powered by AWS and Kaggle

## Contents:

* [Dog breed classifier using CNN's](https://github.com/raviteja-ganta/Machine-Learning-Engineer-Nano-degree-Udacity/tree/master/Dog%20breed%20classifier) - Goal of this project is to use CNN to classify an image in to 133 breeds of dogs. My code will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

  Main steps involved are:
  1) Detect Humans
  2) Detect Dogs
  3) Create a CNN to Classify Dog Breeds from scratch
  4) Create a CNN to Classify Dog Breeds(using Transfer Learning)
  5) Write final algorithm

* [Plagiarism Detector](https://github.com/raviteja-ganta/Machine-Learning-Engineer-Nano-degree-Udacity/tree/master/Plagiarism%20Detector) - Goal of this project is to build a plagiarism detector that examines an answer text file and peforms binary classification, labeling that file as either plagiarized or not, depending on how similar that text file is to a provided, source text

  Main steps involved are:
  1) Clean and pre-process the data
  2) Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
  3) Upload data to S3
  4) Define a binary classification model and a traning script
  5) Create an Estimator in SageMaker
  6) Train the estimator
  7) Deploy the trained model
  8) Evaluate the model
  
* [Deploying a Sentiment Analysis model](https://github.com/raviteja-ganta/Machine-Learning-Engineer-Nano-degree-Udacity/tree/master/Sentiment%20Analysis) - Goal is to create a simple web page which a user can use to enter a moview review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.

  Main steps involved are:
  1) Pre-process the data
  2) Upload the processed data to S3
  3) Build and train the PyTorch model using Amazon sagemaker
  4) Test the trained model
  5) Deploy the trained model for web app
  6) Use the deployed model for web app
     1) Setting up a Lambda function
     2) Setting up API Gateway
  7) Deploying web app


