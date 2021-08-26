# Traffic_CNN

### Background

In this project, we use TensorFlow to **build a neural network to classify road signs** based on an image of those signs. To do so, we’ll need a labeled dataset: a collection of images that have already been categorized by the road sign represented in them. For this project, we’ll use the [**German Traffic Sign Recognition Benchmark**](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news) (GTSRB) [dataset](https://cdn.cs50.net/ai/2020/spring/projects/5/gtsrb.zip), which contains thousands of images of 43 different kinds of road signs.

### Understanding

The downloaded dataset will a zip file named `gtsrb.zip`. After unzipping this file, the `gtsrb` directory will have 43 subdirectories in this dataset. Each numbered subdirectory represents a different category (a different type of road sign). Within each traffic sign’s directory is a collection of images of that type of traffic sign.


### Model Iterations
The base model consists of the following layers:

1. Conv2D layer
2. MaxPool layer
3. Flatten layer
4. Output layer

In further iterations, mulitple Conv2D layers and a fully connecter layer were added to improve model accuracy. The model accuracy results are compared in the python notebook.
