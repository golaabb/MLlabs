# Lab 0: Introduction to Machine Learning with Teachable Machine

In this lab, you will learn to use Google's Teachable Machine, a web-based tool that makes creating machine learning models fast, easy, and accessible to everyone. You'll be creating a simple classifier to differentiate between images of Ferraris and Lamborghinis.

## Step 1: Gather the Dataset

First, you'll need to gather images of Ferraris and Lamborghinis. You can download these from the internet or take pictures yourself. Remember, the more diverse your dataset (different angles, lighting conditions, models of the cars, etc.), the better your model will perform.

## Step 2: Create a New Project on Teachable Machine

1. Go to [Teachable Machine](https://teachablemachine.withgoogle.com/) and click on 'Get Started'.
2. Choose 'Image Project'.
   
## Step 3: Upload Your Dataset

1. Click on 'Upload' under 'Class 1'. Upload your Ferrari images here.
2. Click 'Add Class' to create 'Class 2' and upload your Lamborghini images here.

## Step 4: Train Your Model

1. Click on 'Train Model'.
2. Wait until the training process reaches 100%.

## Step 5: Test and Export Your Model

1. Test your model using the 'Webcam' or 'Upload' option.
2. If you're satisfied with the results, click on 'Export Model'. Choose 'Tensorflow.js' > 'Upload my model' > 'Copy' to get a link to your model.

**Questions:**
Link to the model : https://teachablemachine.withgoogle.com/models/bjEuuuD8S/

- **How does the number and diversity of images in your dataset affect the accuracy of your model? :** I used around 105 images of Lamborghinis and 125 images of Ferraris in different shades, models, colors, and scenarios. It showed 100% accuracy on the images in which it was trained on but was not really able to differentiate when showed Lamborghini and Ferrari in one picture. Majority of the images of Lamborghini were from back side or back right side and it was able to identify those more accurately compared to front images of it so turns out the model the number of images and diversity of the images play a big role in accuracy of a model.
- **What are some limitations of the model you built using Teachable Machine?:**  At first, I downloaded images in bulk from Instagram accounts of Lamborghinis and Ferraris which was 1000 to 1500 images uploaded it in bulk and when starting training it became responsive turns out teachable machine doesn’t support large volume datasets which leads to poor training of the model as the dataset isn’t diverse.

**External Reading:**
1. [Teachable Machine FAQ](https://teachablemachine.withgoogle.com/faq)
2. [Teachable Machine Inspect](https://github.com/googlecreativelab/teachablemachine-community/tree/main/libraries/inspect)

Congratulations! You have created your first image classification model using Google's Teachable Machine. In the subsequent labs, you'll delve deeper into the machine learning models that power these tools.
