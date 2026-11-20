# MobileNetV2-Model
Deep Convolutional Neural Network Approach for Multi-Class Classification of Cancer Medical Images
# Introduction
This project has been developed in google colab, to run the project, you will require the following as described below. 
# Development environment setup
Setup a google colab pro environment:This gives 100 compute units per month, Faster GPU, More memory. This has a cost implication of 9.99USD/month.
# Dataset setup and access 
1. Download the dataset from the url: https://www.kaggle.com/datasets/obulisainaren/multi-cancer 
2. Upload it to your Google Drive. Go to drive.google.com, then New, File upload, and select the zip.
3. Make it accessible to the notebook. Right-click the file, choose Share, and under General access select Anyone with the link with the Viewer role.
4. Copy the file ID. Click Copy link. The link looks like this:
    https://drive.google.com/file/d/<FILE_ID>/view?usp=sharing
    The file ID is the string between /d/ and /view
5. Update the configuration cell in the notebook with your ID:
    FILE_ID = "<YOUR_FILE_ID>"

# Running the note book
Run the notebook from top to bottom. It will download the zip to /content/, extract it, create the train/test split with SEED = 42, and train the model.

# Running project with view access for your reference
https://colab.research.google.com/drive/1IOFCHRAaebcj_LySBXq7uODy1VGJFuQy?usp=sharing 