# Indian Bird Species Image Classification.

Dataset is from Kaggle. link: https://www.kaggle.com/datasets/arjunbasandrai/25-indian-bird-species-with-226k-images

### Why choose this topic:
While researching for our dataset, we came across this really interesting dataset of different Indian Bird species which seemed exciting to work with, the reason for choosing this dataset.
The goal of this ResNet50V2 bird classification project is to develop a highly accurate and effective model that can correctly identify various bird species from photos.

Due to the large number of bird species(we've taken 25 Indian species in our dataset), many of which have similar physical characteristics, classifying birds is a difficult undertaking. Yet, by learning from a sizable collection of bird photos and using deep learning models like **ResNet50V2**, it is feasible to create a model that can precisely identify between various bird species.

The model may use the pre-trained weights and architecture of the ResNet50V2 model and fine-tune them to perform well on the particular bird classification job by fine-tuning a pre-trained ResNet50V2 model on a dataset for bird classification.
Instead of creating new CNN from start, we Will be using **Microsoft's ResNet50V2** to fine-tune it according to our dataset.

### We also implemented Vision Transformer(ViT) and EfficientNet V2 out of which ViT outperformed EfficientNetV2. Siamese Network was also tried and tested on the dataset.
