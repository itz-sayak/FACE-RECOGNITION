# FACE-RECOGNITION

## Requirement
```
Python 3.6
pip install opencv-contrib-python
```

## Outline
This project consist of 3 parts, which are:

Creating datasets (__facedatasets__.py)

Train the model (running.py)

Face Recognition (__facerecognition__.py)

## How to run ?

Make sure have executable permission. (chmod 777 .)

pip install -r requirements.txt

Please make sure that you have folders called 'datasets' and 'trainer' in the same directory. (Optional, I have put the code so it will create if it's not exist)

Run in the command line the face_datasets.py for taking your face image as datasets. Don't forget to set each person's face to unique ID (You need to edit the code everytime, or maybe just change the id variable to raw_input[OPTIONAL])

If you have more face to be include, change the ID and run the program again

Train your datasets by running __running__.py

Lastly, run __facerecognition__.py

