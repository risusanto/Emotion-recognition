# Project Name : Emotion-recognition
# Table of Content :
1.[Description](#p1)

2.[Installations](#p2)

3.[Usage](#p3)

4.[Dataset](#p4)



![](https://github.com/omar178/Emotion-recognition/blob/master/emotions/Happy.PNG)
![](https://github.com/omar178/Emotion-recognition/blob/master/emotions/angry.PNG)




<a id="p1"></a> 
# Description:


However, before we get started, it’s important to understand that as humans. We are never 100% happy or 100% sad. Instead, our emotions mix together.
When experiencing “surprise” we might also be feeling “happiness” or “fright”. And even during the “scared” emotion, we
might feel hints of “anger” as well.
When studying emotion recognition, it’s important to not focus on a single class label. Instead, it’s much more advantageous for us to
look at the probability of each emotion and demonstrate it to see how a person is happy, frightened, sad, disgust and even surprised .
## What does Emotion Recognition mean?

Emotion recognition is a technique used in software that allows a program to "read" the emotions on a human face using advanced image processing. Companies have been experimenting with combining sophisticated algorithms with image processing techniques that have emerged in the past ten years to understand more about what an image or a video of a person's face tells us about how he/she is feeling and not just that but also showing the probabilities of mixed emotions a face could has.

<a id="p2"></a> 
# Installations:
-keras

-imutils

-cv2

-numpy

<a id="p3"></a> 
# Usage:

The program will creat a window to display the scene capture by webcamera and a window representing the probabilities of detected emotions.

> Demo
-run real_time_video.py

You can just use this with the provided pretrained model i have included in the path written in the code file, i have choosen this specificaly since it scores the best accuracy, feel free to choose any but in this case you have to run the later file train_emotion_classifier
## If you just want to run this demo instead of training the model from scaratch, the following content can be skipped
> Train
-run train_emotion_classifier


<a id="p4"></a> 
# Dataset:

I have used [this](https://www.kaggle.com/c/3364/download-all) dataset

Download it and put the csv in fer2013/fer2013/

-fer2013 emotion classification test accuracy: 66%


# Credits
This work is inspired from this fascinating [work](https://github.com/oarriaga/face_classification) 

# Ongoing 
Draw emotions faces next to the detected face.

# Issues & Suggestions

If any issues and suggestions to me, you can create an [issue](https://github.com/omar178/Emotion-recognition/issues).

If you like this work please help me by giving me some stars.
