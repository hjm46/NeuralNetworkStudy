# Neural Network Study

## Objective
The goal of this project is to understand how the internal workings of a neural network works, and how it makes decisions. The idea of this project came out of an interest in knowing when to use different types of neural networks, and the math behind the black box. I will be using image classification with computer vision for this research.

### Image Data
The image data used to train this neural network has been entirely created by me alone. As the purpose of this project is to understand how a neural networks works, we want the training dataset to be as clear and controlled as possible. As such the images use for training are as simple. The training images all have the following properties:
- black on white background
- 10x10 pixels in dimension
- the handwritten letter X or O

There will be 10 samples of the letter X, 10 of the letter 0, and 5 simple examples of neither to start. The validation set will consist of 5 samples from this dataset, and the testing set will consist of 5 unique unseen samples. Of course computer vision training with real data will include images in color, various sizes, and various resolution. Before training these factors will need to be normalized. Additionally, this is not nearly sufficient data to classify these images in any capacity. The dataset will be expanded if needed. These problems concern the dataset, not the properties of the neural network, so we will not study them.
The neural network will classify the image as the letter X, the letter O, or neither if the probability does not meet a certain threshold.
