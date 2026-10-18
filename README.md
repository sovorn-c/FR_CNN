# FR_CNN — Face Recognition with a CNN

Bachelor's final project (B.S. Management of Information Systems, Paragon International University, 2020).

A small end-to-end face recognition pipeline built with OpenCV, dlib, and Keras:

- `face_taker.py` / `Dataset Maker.py` — capture face images from a webcam (Haar cascade detection) and build a labelled dataset
- `Model.py` / `face_training.py` — define and train a convolutional neural network classifier
- `face_recognition.py` — run real-time recognition with the trained model (`trained_model_testing.h5`)

The original face-image dataset is not included for privacy; `Dataset Maker.py` recreates one from a webcam into `dataset/`.

Kept as a record of early computer-vision work; not maintained.
