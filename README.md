# Sign Language Recognition using Random Forest Classifier — Intel oneAPI Optimised Scikit-Learn Library
## Problem Statement
American sign Language, is a natural language that serves as the predominant sign language of Deaf communities. But, deaf people often have difficulties talking to abled people because not everyone knows all the alphabets of sign langauge. So, we need a mechanism to automate this.<br>
## Solution Strategy
signlanguage_recognition is a Model which can detect hand postures fron real-time video and show the alphabet associated with it. This model can detect all the ASL alphabets ranging from A to Z (excluding J and Z).<br>
The dataset is made manually by running the __*collecting_data.py*__ that collects images from your webcam for all the above mentioned alphabets in the American Sign Language :<br>
## Dependencies
opencv-python
mediapipe
scikit-learn intelex
## To run signlanguage_recognition
~~~~
pip install scikit-learn intelex
pip install opencv-python
pip install mediapipe
$git clone https://github.com/RKJenamani/J.A.R.V.I.C..git 
$cd signlanguage_recognition
$python model_test.py
~~~~
