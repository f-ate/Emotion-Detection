# Emotion-Detection

# Emotion Based Song Recommendation

music recommendation system/music player which will detect the user's face,
identify the current mood and then recommend a playlist based on the detected mood.
## Aim and Objectives

#### Aim

To create a music recommendation system/music player which will detect the user's face,
identify the current mood and then recommend a playlist based on the detected mood.

#### Objectives

➢ The main objective of the project is to create an online web-based application(website)
that allows users to get recommendations according to their current emotional state.

➢ Using appropriate datasets for recognizing and interpreting data using machine learning.

➢ To recommend songs according to the emotions recognized using machine learning
model and play in YouTube.
## Abstract

• A user's emotion or mood can be detected by his/her facial expressions. These
expressions can be derived from the live feed via the system's camera.

• A lot of research is being conducted in the field of Computer Vision and Machine
Learning (ML), where machines are trained to identify various human emotions or
moods. Machine Learning provides various techniques through which human emotions
can be detected.

• One such technique is to use Resnet Net-50 model with Keras, which generates a small
size trained model and makes ML integration easier.

• People often use music as a means of mood regulation, specifically to change a bad
mood, increase energy level or reduce tension.

• Also, listening to the right kind of music at the right time may improve mental health.
Thus, human emotions have a strong relationship with music.
## Introduction


• This project is based on an Emotion detection model with modifications. We are going
implement this project with Machine Learning.

• This project can also be used gather to the information about human emotional
condition, i.e. Mood swings, Temporal behaviour.

• Human emotions can be broadly classified as: fear, disgust, anger, surprise, sad, happy
and neutral.

• A large number of other emotions such as cheerful which is a variation of happy and
contempt can be categorized under this umbrella of emotions.

• These emotions are very subtle. Facial muscle contortions are very minimal and
detecting these differences can be very challenging as even a small difference results in
different expressions.

• Also, expressions of different or even the same people might vary for the same emotion,
as emotions are hugely context dependent.

• While the focus can on only those areas of the face which display a maximum of
emotions like around the mouth and eyes, how these gestures are extracted and
categorized is still an important question.

• Neural networks and machine learning have been used for these tasks and have obtained
good results.

• Machine learning algorithms have proven to be very useful in pattern recognition and
classification, and hence can be used for mood detection as well.
## Literature Review

• Currently there are different methodology proposed by researchers to classify the
emotional state of human behavior. We have only focused on some of the basic emotion
of human.

• Various algorithms has been developed to study the facial curve and predict the nature
using feature curves generated using keras.

• This technique uses several learning methods to deduce emotions, which makes the
model expensive to calculate.

• Detecting the emotion based on facial expression has a complexity as every persons face
structure differ from each other hence Haar-cascade is use to read the face structure data
and OpenCV to convert frame data In a structure of array.

• Many approaches have been developed to extract the facial Properties. There are very
few systems available that have the ability to create an emotion based songs playlist
using human emotions.

• It is complex in terms of time to extract facial features in real time.
Existing systems can create a playlist but with less accuracy.
## Methodology

The mood-based music recommendation system is an application that focuses on
implementing real time mood detection.
It is a prototype of a new product that comprises two main modules: Facial expression
recognition/mood detection and Music recommendation.
    
    A. Mood Detection Module
#### This Module is divided into two parts:

    • Face Detection

        ➢ Ability to detect the location of face in any input image or frame. The output is
        the bounding box coordinates of the detected faces.
        ➢ For this task, initially the python library OpenCV was considered. But
        integrating it was a complex task so the Face Detector class available in Java
        was considered.
        ➢ This library identifies the faces of people in a Bitmap graphic object and returns
        the number of faces present in a given image.

    • Mood Detection
        ➢ Classification of the emotion on the face as happy, angry, sad, neutral, surprise,
        fear or disgust.

        ➢ So, Resnet Net-50 which is a CNN architecture model for Image Classification
        and Vision was used.

        ➢ There are other models as well but what makes Resnet Net-50 special is that it
        has very less computation power to run or apply transfer learning to.
        
        ➢ Resnet Net-50 was used with Kera’s to train and test our model for seven
        classes - happy, angry, neutral, sad, surprise, fear and disgust. We trained it for
        25 epochs and achieved an accuracy of approximately 75%.

    B. Music Recommendation Module
        
        • The dataset of songs classified as per mood was found on Kaggle for two different
        languages - Hindi and English.
        
        • Research for a good cloud storage platform to store, retrieve and query this song
        data as per user's request was conducted. Options like AWS, Google Cloud, etc.
        were found but these were rejected as they were costly and provided very limited
        storage for free.
        
        • The mp3 versions of the songs were manually uploaded on Firebase storage and
        were linked in the Real Time database as per mood and language.
## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Advantages

➢ The Emotion Based Music Player system will be of great advantage to the user
looking for music based on there moods and emotional behaviour.

➢ It will help to reduce the searching time.

➢ User can play song effortlessly.

➢ Songs will be played according to the user's mood.

➢ User can also download songs from this application.
## Application

➢ Plays songs according to user mood and emotions.

➢ Recommended for YouTube.
## Future Scope

➢ As we know technology is going to automation so this project is one of the step
towards automation.

➢ Thus, for more accurate results it needs to be trained for more images, and for a
greater number of epochs.

➢ Recommendation of movies and TV series on the basis of mood detection can also
be considered as a future scope for our project.

➢ Now a days people is widely use voice assistance but what about dump people they
will not able to use Google assistance so like this people the application is very
useful.
## Conclusion

➢ In This Project We Are Trying To Help User And Recommend Them Songs
According To Their Emotions. The Emotion-Based Music Player Is Used To
Automate And Give A Better Music Player Experience For The End User.

➢ The Application Solves The Basic Needs Of Music Listeners Without Troubling
Them As Existing Applications Do, It Uses Technology To Increase The
Interaction Of The System With The User In Many Ways.

➢ It Eases The Work Of The End-User By Capturing The Image Using A Camera,
Determining Their Emotion, And Suggesting A Customized Play-List Through
A More Advanced And Interactive System.

➢ A Set Of Emotions Which Can Be Differentiated From Each Other With Certain
Facial Expressions.

➢ The Expression On A Person's Face Can Be Used To Detect Their Mood, And
Once A Certain Mood Has Been Detected, Music Suitable For The Person's
Detected Mood Can Be Suggested.

➢ Our Model, Having The Accuracy Of Approximately 75%, Is Able To Detect
Seven Moods Accurately: Anger, Disgust, Fear, Happy, Sad, Surprise And
Neutral; And Our Android Application Is Able To Play The Music That Would
Be Suitable For The Detected Mood.
## Refrences

[1] Technology used: https://flask.palletsproiects.com/en/2.0.x/

[2] Django documentation: https://docs.diangoproiect.com/en/3.2

[3]Library used: https://www.tensorflow.org/api docs https://keras.io/https://github.com/iperov/DeepFaceLab
