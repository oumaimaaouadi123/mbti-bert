# Introduction

This deep learning project aims to predict Twitter users personality type using MBTI as personality classification model and BERT algorithm as a classifier.
In this document, we will explain to you how to open this project and test it yourself.


# Opening the notebook with google colab
Google Colaboratory is a free online cloud-based Jupyter notebook environment that allows you to train your machine learning and deep learning models on CPUs, GPUs, and TPUs

To open a notebook in google colab to need to :
  - Sign in into your gmail account
  - Go to https://colab.research.google.com
  - Go to File > Upload Notebook > Choose a file
  - Select the .ipynb file you want to open from your computer

# Importing files

To upload a file to google colab, you need to:
  - Go to the side bar and click in "Files" icon
  - Click on the "Upload to session storage" icon
  - Choose the file you want to upload from your computer

In our case, we need to upload two files :
  - The dataset file "mbti_1.csv" which is on kaggle website, you can download it from this link: https://www.kaggle.com/jordiruspira/determining-personality-type-using-ml/data
  - The model file "finetuned_BERT_epoch_4.model" which contains the model we worked on and saved, and you can download it from this link: https://drive.google.com/file/d/1aqrKVW1vPpEXQwXx-8wihngE5GEXiLhC/view?usp=sharing

# Selecting the runtime type

As we explained, google colab gives you access to hardware ressources, such as RAM, disk storage, CPUs and eventually GPUs.

Running your Machine Learning / Deep Learning models on CPUs will cost you a lot of time, so it recommanded that you run them on GPUs.

In order to do so, you need to :
  - Go to "Runtime"
  - Click on "Change the runtime type"
  - Choose the "GPU" option and save

Selecting this option will help your models train faster and return results in a very short period of time.

# Running the code

You can run your code cell by cell or go to Runtime > Run all