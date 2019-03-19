# kse_masters_workshop_introdlcv

This is a repo for Workshop of my Course "Introduction to Deep Learning and Computer Vision" to the Master of Business and Management in Artificial Intelligence and Data Analytics Program (MBAI) students.

During the Course, students without advance knowledge of programming will learn how to build an Object Classification Model using crapped data from the internet. 
I hope they will come up with great and exciting projects! 

At the workshop, we will use Google Colab. 
It is a great tool for training ML models, as it allows using GPU Tesla K80, that perfectly fits for our research purpose.
Also, we will use [FastAI](https://github.com/fastai/fastai) library. 
The fastai library simplifies training fast and accurate neural nets using modern best practices.

The uploaded materials show an example of how to build an Object Classification Model for classifying images of "pizza", "salad" and "spaghetti".

The structure:
* data scrapping using [Google Images Download library](https://github.com/hardikvasa/google-images-download)
* data augmentation examples 
<img src="/images/augmentation.jpg" width="400" height="300">
* model training and analysis of the important statistics like loss functions and accuracy metric during training 
<img src="/images/performance_plot.jpg" width="400" height="300">
* results interpretation using confusion matrix and heatmap analysis <img src="/images/conf_matrix.jpg" width="400" height="300"> 
<img src="/images/analysis.jpg" width="400" height="300">
* final step is to load previously saved weight and make a prediction to a custom image




