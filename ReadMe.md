# Image Classification - Modified MNIST dataset
### Contributors: Nikhil Podila, Shantanil Bagchi, Mehdi A
### Mini-Project 3 - COMP 551 Applied Machine Learning - McGill University

## Abstract
In this project, a novel approach is proposed for classiﬁcation of the Modiﬁed MNIST dataset. The task is to identify the numerically largest value among three handwritten digits within each image. The proposed algorithm is a modiﬁed version of the well known VGGNet. Since convolutional neural networks (CNN) automatically capture the relevant features, we observe that additional feature selection and preprocessing on dataset are unnecessary. We also observe that data augmentation, optimizer tuning and model ensembling contribute to our best performance. The proposed algorithm reached an accuracy of 99.3% on the test set and ranked the ﬁrst on Kaggle’s Modiﬁed MNIST competition.

## Repository Structure
The repository contains 3 files:
* 1 Jupyter notebook file - Miniproject3_Submission.ipynb
* 1 ReadMe file - ReadMe.md
* 1 Project writeup - writeup.pdf

## Dataset
The Modified MNIST dataset is hosted on Kaggle at: <br> https://www.kaggle.com/c/modified-mnist/data

## Code Usage - (Google Colab - Python 3.7)
1. Open Jupyter notebook in Google Colab using a Google account (https://colab.research.google.com)
2. Upload the notebook Miniproject3_Submission.ipynb
3. Switch Runtime type to GPU to ensure faster execution
4. The second code block contains Google Drive connection. Ensure that connection is established and Change directory into directory where the dataset files are stored.
5. Run all the cells. 
