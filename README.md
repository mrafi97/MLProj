# Machine Learning
Facial recognition implementation using Keras VGG face

## Project Summary
* This project uses Open CV library to locate a face in real time from video recording and the face will be classified as either Yining, Mohammad, or a stranger. This recognition is accomplished by fine-tuning a pre-trained deep neural network(VGG Face) in which the final layers of the network are retrained to fit this objective.
* We used 600 pictures for training and 100 pictures for testing the fine-tuned model. Each picture is resized to 64 * 64 pixels.

## Table of content for code
* [Training algorithm] (https://github.com/YinWang3026/MLProj/blob/master/Detailed_Proj.ipynb)
* [Resizing images] (https://github.com/YinWang3026/MLProj/blob/master/Resizing.ipynb)
* [Training Images](https://github.com/YinWang3026/MLProj/blob/master/train.zip)
* [Test Images] (https://github.com/YinWang3026/MLProj/blob/master/train.zip)
* [Real time face detection] (https://github.com/YinWang3026/MLProj/blob/master/facecam_detection.py)
*
## Built with:
 * Tensorflow
 * Keras
 * Open CV
 * [VGG Face](https://github.com/rcmalli/keras-vggface)
 * Flickerapi
 
## Contributors:
* Sihao Chen
* Mohammad Rafi
* Yining Wang

## References
1. Cropping Faces
   1. [Directory images](https://codereview.stackexchange.com/questions/156736/cropping-faces-from-images-in-a-directory)
   2. [Webcam](https://realpython.com/face-detection-in-python-using-a-webcam/)
2. [OpenCV images conversion](https://aboveintelligent.com/face-recognition-with-keras-and-opencv-2baf2a83b799)
3. [Saving Keras Model] (https://machinelearningmastery.com/save-load-keras-deep-learning-models/)
4. [CNN lab 8](https://github.com/sdrangan/introml/blob/master/unit08_cnn/lab08_fine_tune_partial.ipynb)
