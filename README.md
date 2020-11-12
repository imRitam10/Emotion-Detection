Requirements=>
numpy
opencv-python
tensorflow

to train this model, use:
python emotions.py --mode train

To view predictions use:
python emotions.py --mode display

The folder structure is of the form:
data (folder)
emotions.py (file)
haarcascade_frontalface_default.xml (file)
model.h5 (file)


This implementation by default detects emotions on all faces in the webcam feed. the test accuracy reached 90% in 60 epochs.

