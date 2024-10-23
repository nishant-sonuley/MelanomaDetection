# Melanoma Detection
This project builds a machine learning model to detect melanoma and other types of skin cancer from images using a Convolutional Neural Network (CNN).

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Background: Melanoma is a dangerous type of skin cancer. Early detection is important to save lives. This project aims to help doctors by automatically identifying melanoma and other skin diseases from images.
- Business Problem: Doctors currently need to manually review images to diagnose skin conditions. This takes a lot of time. The project’s goal is to create a model that can quickly and accurately classify skin images into different disease categories.

- Dataset:
- The data is from the International Skin Imaging Collaboration (ISIC) and contains images of 9 types of skin conditions, including melanoma.
- Some disease categories have more images than others, so data augmentation is used to create a balanced dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python - version 3.8
- TensorFlow/Keras - version 2.10
- Augmentor - version 0.2.8

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- Balancing the Data: Adding more images to the under-represented classes improved the model's performance.
- Data Augmentation: Using data augmentation (like rotating, flipping, and zooming images) helped the model perform better by seeing more varied examples.
- The model has potential to converge more, so increasing the number of epochs would likely lead to better results.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Acknowledgements
- Thanks to Upgrad for this assignment.
- The dataset was provided by the International Skin Imaging Collaboration (ISIC).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
