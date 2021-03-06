# Semantic Segmentation
### Overview
This project contains an implementation of a Fully Convolutional Neural Network as described in [this paper](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf). This project was created as a coursework for [Udacity's Self-Driving Car Engineer Nanodegree](https://in.udacity.com/course/self-driving-car-engineer-nanodegree--nd013/?).

### Result

The FCN was trained for 25 epochs on an AWS GPU 3.4X server. The resulting images can be found in the processed_images folder. Here are some samples -

![Sample 1](./processed_images/um_000000.png)

![Sample 2](./processed_images/um_000020.png)

![Sample 3](./processed_images/um_000090.png)

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook, system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

