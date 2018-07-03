# Facial Emotion Recognition using Machine Learning

## Getting Started
Emotion detection has become a topic of continuous research and innovation as over
the past decade the limitations of computer vision have been lifted by the introduction
of machine learning. As machine learning algorithms leverage the huge computation
power of GPU’s, the image processing capabilities of these models fit suitably with
real world problems. Computer vision has spread from a novel domain to several other
domains such as the behavioral sciences. These algorithms or models are being used
in various real world applications across several fields such as security, driver-safety,
autonomous vehicles, human-computer interaction and healthcare. These models are
continuously evolving due to the introduction of graphical processing units which are
hardware equipments capable of performing millions of computations within mere seconds
or minutes. The emergence of technologies such as augmented reality and virtual
reality are also dependent on these GPU’s heavily. Hence, combining the statistical intelligence
of machine learning algorithms and the processing power of GPU hardware,
we are able to create breakthrough models capable of detecting emotions from static
images as well as video feeds.

The project work entitled "Facial Emotion Detection Using Machine Learning" would
envisage the following: 
1. Capturing static images for pre-processing. 
2. Feature Extraction
using Deep Neural Networks. 
3. Implementing a convolutional neural network to classify images based on the aforementioned features

### Dataset
We are using the Cohn-Kanade dataset available here http://www.consortium.ri.cmu.edu/ckagree/. The dataset we used for training our model is an augmented version of the CK+ dataset.

![38](https://user-images.githubusercontent.com/28685502/42219980-46dd4b50-7eeb-11e8-9941-150872bf49db.jpg)
![aug_0_927](https://user-images.githubusercontent.com/28685502/42219981-47181fdc-7eeb-11e8-8cf2-d8646cbb3cf6.jpeg)

This is done so as to increase the number of samples for training our model.The total size of our dataset is 2536 samples.

## Requirements
* Python 3.5 or above
* Tensorflow 1.6
* Keras 2.1.0
* OpenCV
* scikit-learn
* Numpy
* Matplotlib
* itertools

## Training the model
Install the required libraries and run this file. Training takes a while to complete, but it can be sped up by using GPU options.
```python
python fred_train.py
```
## Running Test
To test the model make sure your webcam is working or attach an external webcam is online. 
```python
python facialmore.py
```

## Results
* Threshold Accuracy: 86.98%
* Test Loss: 1.868 Validation Loss: 0.973
* Test Accuracy:0.705 Validation Accuracy:0.721
* Confusion Matrix
