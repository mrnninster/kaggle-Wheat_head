## kaggle-Wheat_head
Creation of a set of object detection models that are able to count wheat head in a image.


## Problem
Counting Detected wheat head in an image, using object recognition.

## Proposed Solution
This project was created to count the number of wheat heads detected in an image, it also has the possibility of generating a list of files that tell you exactly where the object identified are located in the image.

In this projecti will be leveraging both resnet a pretrained model, ResNet50 trained on coco dataset and keras-retinanet from this repository https://github.com/fizyr/keras-retinanet.git, the script for creating the models contained in this repository is Wheathead.ipynb, all the training process was carried out google collab. 

The neural network was trained using 3422 wheathead images, the test dataset contains 10 images. I will do my best to show you the implementation process but i would really just advice that you run the script *Wheathead.ipynb* this project project was inspired by the kaggle wheathead competition and the dataset used is just a part of the dataset available in the competition  


# Used Stack

- Python


# Benefits

- Provision of an software to help agriculturist and farmers estimate their wheat head yields.
- Creation of an agriculturally inclined A.I system.


#   Proposed directory layout

    .
    ├── Keras-retinanet         # Contains the keras retinanet files as well as the created models
    ├── train                   # Training images
    ├── test                    # Test Images
    ├── Wheathead.ipynb         # Training and Inference file
    └── README.md               # information and Instructions of Use


# How to setup project and run locally
You will need the following to run the neural net script for infrence
- Keras-retinanet
- Tensorflow
- matplotlib
- sklearn
- Open CV
- seaborn
- pandas
- numpy

### Clone the repository 
```
https://github.com/mrnninster/painter.gitt
```

## Creating your model using google collab



![](screenshots/Screenshot%20(120).png)


![](screenshots/Screenshot%20(121).png)
