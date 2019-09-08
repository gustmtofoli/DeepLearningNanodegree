## Deep Learning Nanodegree

This is a repo containing my progress in the Udacity Nanodegree: Deep Learning.

## Projects

- Bike Sharing: 
  - implementation of a Multilayer Perceptron Neural Network (without libs/frameworks) to predict bike sharing usage based on previous years usage data.

- Dog Breed: 
  - implementation of a Convolutional Neural Network with Pytorch to predict and detect dog breeds from an image.
  - impementation of a [transfer learning](https://towardsdatascience.com/a-comprehensive-hands-on-guide-to-transfer-learning-with-real-world-applications-in-deep-learning-212bf3b2f27a) model to predict dog breeds from an image.
  - Detect human faces and predict the dog breed that best fits the face in the image.

- Generate TV Scripts:
  - implementation of a [Recurrent Neural Network with Long Short-Term Memory](https://www.bioinf.jku.at/publications/older/2604.pdf) to generate a TV Script.

- Generate Faces:
  - implementation of a [Generative Adversarial Network](http://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf) to generate faces based on celebrities faces.
  
- Deploying a Sentiment Analysis Model:
  - implementation of a Recurrent Neural Network to predict POSITIVE and NEGATIVE movie review on AWS SageMaker
  - creation of a POST endpoint on a service on AWS API Gateway.
  - creation of a lambda function that receive the review from a simple web app and returns the response (POSITIVE/NEGATIVE) from the model.