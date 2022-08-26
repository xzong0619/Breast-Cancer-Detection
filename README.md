# Predicting invasive ductal carcinoma (IDC) in tissue slices
<p align="center">
  <img src="https://github.com/xzong0619/Breast-Cancer-Detection/blob/main/images_for_readme/IDC_illustration.png" alt="IDA illustration"/>
</p>

## Motivation
Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma (IDC) is the most common form of breast cancer. It develops in a milk duct and invades the fibrous or fatty breast tissue outside the duct. Accurately identifying and categorizing breast cancer subtypes is an important clinical task, and automated methods can be used to save time and reduce error.

## Dataset Description
- 279 patients; 162 of them diagnosed with IDC, 113 slides used for training and 49 used for testing.
- 277,524 image patches of 50*50 pixel RGB extracted from 162 whole mount slide images of breast cancer speciemens scanned at 40x. 198,738 IDC negative and 78,786 IDC positive.

## Evaluation metrics
- F1 score
- Balanced accuracy
- Precision
- Recall

## Healthy tissue patches examples
![healthy patches](https://github.com/xzong0619/Breast-Cancer-Detection/blob/main/images_for_readme/healthy_patches.png)

## Cancer tissue patches examples
![cancer patches](https://github.com/xzong0619/Breast-Cancer-Detection/blob/main/images_for_readme/cancer_patches.png)

## Refereces
Original paper with the dataset: [Automatic detection of invasive ductal carcinoma in whole slide images with Convolutional Neural Networks](https://www.researchgate.net/publication/263052166_Automatic_detection_of_invasive_ductal_carcinoma_in_whole_slide_images_with_Convolutional_Neural_Networks)

## What to do next
- Develop a live web app to help speed up a pathologist's workflow and provide diagnosis support
