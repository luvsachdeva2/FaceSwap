# Face Swap with Python and dlib

## Overview

This Python application allows you to perform face swaps in images using the dlib library with the pre-trained model `shape_predictor_68_face_landmarks`. By identifying and swapping facial landmarks, you can create fun and creative face swap images.
<img width="1273" alt="Screenshot 2023-10-10 at 10 25 20 PM" src="https://github.com/RishabhSrivastava-17/FaceSwap/assets/72572136/96863e59-f6bb-46f6-a6bd-91272ca2ee2b">

Clone or download this repository to your local machine.
Place the images you want to perform face swaps on in the project directory.
Run the face_swap.py script
Follow the on-screen instructions to select the source and target images for the face swap.
The script will process the images, identify facial landmarks, and perform the face swap.
The resulting face-swapped image will be saved in the project directory.
Example
## Requirements

Before you begin, make sure you have the following prerequisites installed:

- Python (3.6+ recommended)
- dlib library
- OpenCV (cv2)
- Numpy

You can install these dependencies using `pip`:

```bash
pip install dlib opencv-python numpy
