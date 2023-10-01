# Skin-Cancer-Detection-using-CNN:
Building and Optimizing Melanoma Skin Detection Problem through Image Identification and Classification using CNN

#### Team Members: Himanshu Yadav, Amit Kumar Chaudhary & Shreeragh Chandrabose 



# Project Name: Melanoma Skin Cancer Detection using CNN Model
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

Melanoma is a type of cancer that can be deadly if not detected early as it accounts for 75% of skin cancer deaths. This project provides an AI solution to dermatologists to evaluate the images and alert the patients of potential risks.

We have used portal provided 2357 images consisting of 9 diseases viz. Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign, keratosis, Seborrheic keratosis, Squamous cell carcinoma and Vascular lesion. We took the following steps to solve the problem:
> Read the data and understood the class imbalance
> Created a baseline model that Overfitted
> Augemented images to few degrees and zoomed it to check if Overfitting reduced. It did.
> Augmented images by inserting 500 images in each class and hence balanced the class imbalance
> The above step not only reduced the overfitting, it also increased the accuracy manifold



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis: Baseline model is ~60% in terms of accuracy due to class imbalance causing high overfitting
- Conclusion 2 from the analysis: After first Augmentation, the accuracy reduced but overfitting reduced as well drastically 
- Conclusion 3 from the analysis: Hence we understood the Augmentation strategy had to be changed to provide better results which we got after using Augmentor library
- Conclusion 4 from the analysis: The final model can now predict the disease class with ~83% accuracy.

## Python Libraries used:
tensorflow, keras
numpy, pandas,
os, pathlib, PIL
google colab, drive
matplotlib, sns

## Download Dataset: https://drive.google.com/drive/folders/1--GDl3-oBjB2X_hpWYayb4j2I3UUXc8J?usp=sharing
Download the dataset : melanoma_skin_cancer_detection_dataset
Arrange it as arranged in the Report.pdf file.
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was a team effort of Himanshu Yadav, Amit Kumar Chaudhary & Shreeragh Chandrabose; who contributed to many model changes and iterations to get the most optimal accuracy out. It was also guided by the notebook provided Mr. Sayan Dey, Upgrad Instructor that led us to the steps to follow and achieve the best results.


<!-- Optional -->
<!-- ## License -->
<!-- You don't have to include all sections - just the one's relevant to your project -->
