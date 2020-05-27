# Fashion Item Classification (Convolutional Neural Networks)
Clothing in many cultures reflects characteristics such asage, social status, lifestyle and gender. Apparel is also an important descriptor in identifying humans, e.g. "the manwearing an orange jacket" or "the woman in red high heels."Given the role of clothing apparel in society, "fashion classification" has many applications. For example, predicting the clothing details in an unlabeled image can facilitate the discovery of the most similar fashion items in an e-commerce database. Similarly, classification of a user’s favorited fashion images can drive an automated fashion stylist, which would provide outfit recommendations based on the predicted style of a user. Real-time clothing recognition can be useful in the surveillance context, where information about individual's clothes can be used to identify crime suspects. Fashion classification also facilitates the automatic annotation of images with tags or descriptions related to clothing, allowing for improved information retrieval in settings such as social network user's photos.

## Problem statement
Fashion training set consists of 70,000 images divided into 60,000 training and 10,000 testing samples. Dataset sample consists of 28x28 grayscale image, associated with a label from 10 classes. 

The 10 classes are as follows:  
0. T-shirt/top
1. Trouser
2. Pullover
3. Dress
4. Coat
5. Sandal
6. Shirt
7. Sneaker
8. Bag
9. Ankle boot

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. 

## Technical Requirements
This Project has the following software requirements:
- Python 3.7
- Anaconda
- Jupyter Notebook
