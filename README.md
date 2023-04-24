# Image Classification for E-Commerce

## Data Overview
The dataset used for training and testing the product recognition model includes images from 2,019 product categories with one ground truth class label for each image. The dataset consists of a total of 1,011,532 images for training, 10,095 images for validation, and 90,834 images for testing.

## Data Source
The data source for the dataset is [www.kaggle.com/competitions/imaterialist-product-2019/data](https://www.kaggle.com/competitions/imaterialist-product-2019/data).

## Methodology
For this project, a Similar Images Finder was developed for online shopping to search similar product images for improved e-commerce accuracy. A dataset of 10 Lakh+ images for training and 90K+ images for testing was worked on. Features were extracted using MobileNetV weights in ElasticSearch and KNN was implemented in ElasticSearch to find the most similar images for a queried image.

## Future Work
Future work includes deploying the application on the AWS cloud platform to make it easily accessible to users. Additionally, the model's accuracy will be further improved by fine-tuning the parameters and exploring additional features.
