Image Classification with ResNet50
This project demonstrates how to use the pre-trained ResNet50 model to classify images. The code loads an image, preprocesses it, and then uses the ResNet50 model to predict the top classes of the image. The predictions are displayed along with the input image.

Requirements
numpy
matplotlib
opencv-python
keras
You can install the required packages using pip:

نسخ الكود
pip install numpy matplotlib opencv-python keras
Usage
Place your image in the same directory as the script or provide the path to the image.
Modify the img_path variable in the script to point to your image file.
Run the script. It will display the input image and output the top predictions.
Example:
For the input image cat3.jpg, the script will output the following predictions:

makefile
نسخ الكود
Predicted:
Egyptian_cat: 0.5891
lynx: 0.2163
Siamese_cat: 0.1589
Functions:
load_image(img_path): Loads and preprocesses the input image.
predict_image(model, img_path, top=3): Makes predictions on the input image and returns the top classes.
