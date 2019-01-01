## Articles
Articles that helped me understand stuff
Excellent article on convolutions:
https://medium.freecodecamp.org/an-intuitive-guide-to-convolutional-neural-networks-260c2de0a050

### What is convolution?
Convolution is a mathematical operation performed on 2 functions to ouput a 3rd function that expresses how one input is modified by the other.

### And how does convolutions help in neural networks?
The idea comes from how visual cortex in brain interprets from visual inputs from eyes. The visual cortex as 2 types of cells - S(simple) cells and C(complex) cells. Simple cells identify the local part of an image like edges, angles while Complex cells work on top of simple cells to identify the whole image. 

### How does convolutional neural network work?
CNNs have 2 components that do the thing:
1. Hidden layer / feature extraction part: This is where individual features are extracted. Like ear on a face, wheel of a car. The hidden layer uses techniques of:
  a) Convolutions 
  b) Pooling.
2. Classification part: On top of the extracted features, this classifier assigns the probability of image being a certain object. Like the object has 80% chance of being a cat.

## Feature extraction: Convolution and Pooling

### How does convolution work?
Convolution is a mathematical combination of 2 functions to produce 3rd function. Input data is 1s function and the kernel(filter) is the 2nd function. These both are combined to produce feature map (the 3rd function).

#### How do the 1st and 2nd functions are combined?
Feature map is obtained by sliding the kernel or filter over the input. At each location matrix multiplication is performed to sum up the result into feature map.

Numerous convolutions are performed using different kernels/filters resulting in different numerous feature maps. 

### What is pooling?
After convolution layer, pooling layer is added. Pooling layer is added to reduce the dimensionality to reduce the number of parameters and computation in the network.


##How does back propagation work in CNNs?
