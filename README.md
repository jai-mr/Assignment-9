* Repository github url : https://github.com/jai-mr/
* Assignment Repository : https://github.com/jai-mr/Assignment-9
* Submitted by : Jaideep Rangnekar
* Registered email id : jaideepmr@gmail.com

## Objective to achieve the use of RESNET18 model on the CIFAR-10 dataset:
1. Move your last code's transformations to Albumentations. Apply ToTensor, HorizontalFlip, Normalize (at min) + More (for additional points)
2. Please make sure that your test_transforms are simple and only using ToTensor and Normalize
3. Implement GradCam function as a module. 
4. Your final code (notebook file) must use imported functions to implement transformations and GradCam functionality
5. Target Accuracy is 87%
6. Details captured 
    Training Accuracy : 95.57 %
    Test Accuracy     : 87.21%   
5. Class wise accuracies
    Accuracy of plane : 91 %
    Accuracy of   car : 93 %
    Accuracy of  bird : 88 %
    Accuracy of   cat : 68 %
    Accuracy of  deer : 89 %
    Accuracy of   dog : 70 %
    Accuracy of  frog : 92 %
    Accuracy of horse : 95 %
    Accuracy of  ship : 91 %
    Accuracy of truck : 91 %


## Jupyter Notebook File reference executed in Colab
[Assignment - 9](https://github.com/jai-mr/Assignment-9/blob/master/09_CodeFinal.ipynb)

## Training/Test - Loss & Accuracy Curve
[Training/Test - Loss & Accuracy Curve](https://github.com/jai-mr/Assignment-9/blob/master/images/TrainTestLossAcc.png)

## Test vs Train Accuracy
[Test vs Train Accuracy](https://github.com/jai-mr/Assignment-9/blob/master/images/TestvTrain.png)

## Mis-Classified Images
[Mis-Classified Images](https://github.com/jai-mr/Assignment-9/blob/master/images/MisClassify.png)

## CIFAR10
Cifar10 is a classic dataset for deep learning, consisting of 32x32 images belonging to 10 different classes, such as dog, frog, truck, ship, and so on. Cifar10 resembles MNIST — both have 10 classes and tiny images. 

## Albumentation
Albumentation is a fast image augmentation library and easy to use with other libraries as a wrapper. The package is written on NumPy, OpenCV, and imgaug. What makes this library different is the number of data augmentation techniques that are available. While most of the augmentation libraries include techniques like cropping, flipping, rotating and scaling, albumentation provides a range of very extensive image augmentation techniques like contrast, blur and channel shuffle. Here is the range of augmentations that can be performed. 

The real power of albumentation is in pipelining different transformations for the image at once. 

CLAHE : Contrast Limited Adaptive Histogram Equalization to equalize images
Cutout : takes out a part of the image that is not very important for classification.
Random rotate : rotates the image by a certain degree
Blur : that reduces the intensity of pixels to appear blur
Optical distortion : This distorts certain elements of the image.
ShiftScaleRotate : Allows you to scale and rotate the image by certain angles. 


[Image Transformations available in Albumentations-1](https://github.com/jai-mr/Assignment-9/blob/master/images/albumentation.png?raw=true)
[Image Transformations available in Albumentations-2](https://github.com/jai-mr/Assignment-9/blob/master/images/albumentation2.png)

References:

[Hands-on Guide To Albumentation](https://analyticsindiamag.com/hands-on-guide-to-albumentation/)

[Albumentations Package for Image Augmentation](https://medium.com/@ArjunThoughts/albumentations-package-is-a-fast-and-%EF%AC%82exible-library-for-image-augmentations-with-many-various-207422f55a24)

[Albumentations](https://github.com/albumentations-team/albumentations)