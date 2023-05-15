# Handwritten-Digit-Recognition
During my internship at CodeClause, I have completed my assigned project on Handwritten Digit Recognition.
Working with the MNIST dataset allowed me to learn the principles of Convolutional Neural Networks (CNN), a particular kind of deep neural network. I learned how to use the Keras library to apply deep learning, how to build a CNN model—which typically consists of convolutional and pooling layers—why CNN works best with grid structures, and other things while working on this project.  

## About the Dataset:
The Modified National Institute of Standards and Technology database, or MNIST dataset, is one of the most well-liked datasets for machine learning and deep learning. It has 10,000 test photos and about 60,000 training images of handwritten digits from 0 to 9. The handwritten digit pictures are represented as a 28 by 28 matrix with grayscale pixel values in each cell. simply a tensor of numbers in the range [0, 255] as picture. Near to 255 is considered dark the closer it comes to zero. Consequently, it has ten separate classifications.  
![image](https://github.com/snehaexe/Handwritten-Digit-Recognition/assets/97626004/a0f2dd35-21d8-4ae6-98b1-f64387e0a06f)

## CNN
A neural network type called a convolutional neural network, or CNN or ConvNet, is particularly adept at processing input with a grid-like architecture, like an image. A binary representation of visual data is a digital image. It is made up of a grid-like arrangement of pixels, each of which has a pixel value to indicate how bright and what colour it should be. CNN has high accuracy, and because of the same, it is useful in image recognition.

A CNN typically has three layers: a convolutional layer, a pooling layer, and a fully connected layer.

### Convolution Layer :
This layer creates a dot product between two matrices, one of which is the kernel—a collection of learnable parameters—and the other of which is the constrained area of the receptive field. Compared to a picture, the kernel is smaller in space but deeper. This indicates that the kernel height and width will be spatially small if the image consists of three (RGB) channels, but the depth will go up to all three channels.

### Pooling Layer :
By calculating an aggregate statistic from the surrounding outputs, the pooling layer substitutes for the network's output at specific locations. This aids in shrinking the representation's spatial size, which lowers the amount of computation and weights needed. Each slice of the representation is subjected to the pooling operation separately.

### Fully Connected Layer :
As in a conventional FCNN, all of the neurons in this layer are fully connected to all of the neurons in the layer before and after. Because of this, it can be calculated using a matrix multiplication followed by a bias effect, as per usual. The representation between the input and the output is mapped using the FC layer.
