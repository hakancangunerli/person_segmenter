# Person Segmenter

I am aware that the name is a little weird, but this script performs person detection and image segmentation on images that you choose. It utilizes OpenCV for image processing and MediaPipe for object detection. The script detects objects in an image, allows the user to select an object, and then segments the selected object.

## Overview

The script first detects objects in an image using a MediaPipe object detection model. After detection, it visualizes these objects with bounding boxes. The user can then choose an object to segment. The script uses the user's selection to perform image segmentation, highlighting the chosen object.

## Requirements

- Python 3.x
- OpenCV (cv2)
- MediaPipe
- NumPy
- Matplotlib
- IPython (for displaying images within Jupyter notebooks)


## Demo

This is the original image before segmentation:

![Original Image](images\000000002299.jpg)


This is the image after segmentation, with the selection of person0 as the selection:

![Person](segmented_images\person.jpg)