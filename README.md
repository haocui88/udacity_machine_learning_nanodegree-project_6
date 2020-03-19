# udacity_machine_learning_nanodegree-project_6

Instructions
Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/udacity/dog-project.git
	cd dog-project
Download the dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.

Download the human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

Obtain the necessary Python packages:


### Project Overview
Computer vision (CV for short) is one of the promising techniques in the machine learning world. The basic idea of the computer vision is to let the computer to see and understand the digital images as human beings do. These digital images will be processed and transformed into digitalized data that the computers could make sense of them by employing machine or deep learning algorithms to train the data. The computer vision techniques could be mostly used to address three types of problems: image classification, object detection, and neural style transfer. With the aid of the deep learning algorithms and exponentially increased digitalized images, the computers are now "smarter" enough to address most of the complex issues, such as classifying different images and detect an object with high accuracy. Given the enormous amount of images of real-world objects, there is a considerable opportunity to explore how computer vision could be applied in identifying and classifying the objects based on the images provided. Convolutional neural net(CNN) is one of the most frequently used algorithms in the computer vision realm to classify the images. There are several variants of the algorithm, depending on the CNN architecture. In this study, I will explore algorithms such as VGG16[1] and ResNet[2] to see how these algorithms could help to classify the images.

### Problem statement
In this project, a machine learning method for image classification will be used by extracting the features from the trained images as the inputs for the model artifact for our classifier. Specifically, I will solve the problem of creating an image classifier to classify the breed of the dog image. Then, I'll write a function to incorporate the human face detector and dog image with the image classifier to detect if the image is a dog or human or something else and provide the results of the dog breed given the CNN image classifier model I trained. Totally, there will be 133 breeds of dog as the label used for the training. 
