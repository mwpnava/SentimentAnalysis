# Deploying a Sentiment Analysis Model

## Project Overview

In this project, I have used Amazon SageMaker to complete an entire lifecycle of a machine learning project. The goal is to build a very simple web page in which a user can submit a movie review and the prediction model behind the scenes will predict whether it is Positive or Negative review. The prediction model is implemented using Pytorch framework and trainned on IMDB dataset.

The objective of this project is to build a web page in which a user can write a movie review and a machine learning model will predict if the rview was POSITIVE or NEGATIVE. The prediction model is a Sentiment Analysis Model, I developed my own neural network using Pytorch as a framework.


### General Outline

- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3 (Amazon Simple Storage Service)
- Step 4: Build and Train the PyTorch Model
- Step 5: Testing the Model
- Step 6: Deploying the model for testing
- Step 6.1: Use the model for testing
- Step 7  Deploy the model for the web app
- Step 7.1: Setting up a Lambda function
-Step 7.2: Setting up API Gateway
- Step 8  Use the model for the web app

### Libraries

The list below represents main libraries and its objects
for the project.
- [Amazon SageMaker](https://aws.amazon.com/machine-learning/accelerate-amazon-sagemaker/g) (Build, train, and deploy a model)
- [Pytorch](https://pytorch.org) An open source machine learning framework that accelerates the path from research prototyping to production deployment

