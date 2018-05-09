# weCycle

weCycle is an app designed to help users categorize materials for recyling. The app uses a neural network to learn which materials are recyclable and give advice.

## Convolutional Neural Network - TensorFlow MobileNet

The app utilizes a neural network to recognize 11 categories of object that are then classified as recyclable or garbage.
The network was created using a 25 layers pretrained model , MobileNet, which includes 5 convolutional layers. 

## Databases

Due to the specific nature of the app, we had to compile our own databases of the images categories to train the neural network using transfer learning. 
**The databases are too large for github, request access if required.

## Android App

The Android application is based on a demo application originally written by Pete Warden (https://github.com/googlecodelabs/tensorflow-for-poets-2).

Modifications:
* RecognitionScoreView.java was modified to include the recycling instructions.
* The graph and label files were updated for the new trained network.
* The XML layouts were modified to customize the app.

## Resources 

* https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2/index.html?index=..%2F..%2Findex#7 
* https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0 
* https://www.tensorflow.org/mobile/tflite/
* https://developer.android.com/guide/
* https://stackoverflow.com
