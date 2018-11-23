

== DRAFT ==


Live Web App: 

This is a prototype for an online tool that can look at a chest x-ray and tell if the patient has Tuberculosis (TB) or not. 

The dataset used to train the model consists of 800 images, which is quite small. Although the accuracy and F1 score are greater than 0.8, I'm uncertain of how well this model will generalize because the validation set had only 120 images. I chose to use as many images as possible for training.

Model F1 score: 0.85

The process used to build and train the model is described in this Kaggle kernel:


The dataset used for the training can be found here:<br>
https://www.kaggle.com/kmader/pulmonary-chest-xray-abnormalities

All javascript, html and css files used to create the web app are available in this repo.
