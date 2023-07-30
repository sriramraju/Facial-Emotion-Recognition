Recognition of facial expressions from gray scale images using Convolutional Neural Networks. 

Background: Facial emotion recognition refers to identifying expressions that convey basic emotions such as fear, happiness, and disgust, etc. It plays an important role in human-computer interactions and can be applied to digital advertisement, online gaming, customer feedback assessment, and healthcare. High emotion recognition accuracy has been achieved in images captured under controlled conditions and consistent environments. Challenges persist in emotion recognition under naturalistic conditions due to high intra-class variation and low inter-class variation, e.g., changes in facial pose and subtle differences between expressions.

Aim: To automatically recognize facial emotions (angry, happy, sad, surprised, disgust, fear and neutral) from gray scale images using Convolution Neural Network (CNN) architecture. 

Dataset: A publicly available dataset of facial expressions on the Kaggle website (https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer). It contains 35,685 examples of 48x48 pixel gray scale images of faces with expressions (happiness, neutral, sadness, anger, surprise, disgust, fear).

Challenges: Achieving an accuracy better than human performance which is reported to be 65.5 %.

Results: Four models are built for recognizing facial expressions from gray scale images. All the models are trained and tested on the same dataset. For consistency purposes, all the models are trained with same optimizer and same number of dense layers. Model #4 performed the best with an overall test accuracy of 65%, which is similar to the human performance reported 65-70%.
