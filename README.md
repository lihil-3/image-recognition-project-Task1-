# Fruit Image Recognition using Teachable Machine

## Project Description

This project is an image classification model created using Google Teachable Machine. The model was trained to recognize three different fruit classes:

- 🍓 Strawberry
- ❤️ Raspberry
- 🍒 Cherry

The trained model was exported in TensorFlow → Keras format and used with a Python script to classify input images.

---

## Tools Used

- Google Teachable Machine
- TensorFlow / Keras
- Python
- NumPy
- Pillow
- Google Colab

---

## Project Steps

1. Created an Image Project in Google Teachable Machine.
2. Added three classes:
   - Strawberry
   - Raspberry
   - Cherry
3. Uploaded multiple training images for each class.
4. Trained and evaluated the model.
5. Exported the model in TensorFlow → Keras format.
6. Loaded the model in Python using Google Colab.
7. Tested the model using three different images.

---

## Files

- task1.py : Python script for loading the model and making predictions.
- keras_model.h5 : Trained Keras model.
- labels.txt : Class labels.
- Ct.jpg : Cherry test image.
- Rt.jpg : Raspberry test image.
- ss.jpg : Strawberry test image.

---

## How to Run

1. Open the project in Google Colab.
2. Upload all project files to the Colab session.
3. Install the required libraries (if needed):
!pip install tensorflow pillow numpy

4. Run the Python script (`task1.py`) or execute all notebook cells.
5. The program will display the predicted class and confidence score for the selected image.

---

## Sample Output
Predicted Class: Strawberry
Confidence: 99%

---

## Author

Hind Almutairi

Computer Science Student
