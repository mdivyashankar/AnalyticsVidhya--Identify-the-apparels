# AnalyticsVidhya--Identify-the-apparels

Website link: https://datahack.analyticsvidhya.com/contest/practice-problem-identify-the-apparels/

<b> Using ResNet34 pretrained model with Pytorch got an accuracy score of 0.912 on test data and rank 343 on leaderboard. </b>

This hackathon is also available as <b> Fashion MNIST </b> on kaggle at: https://www.kaggle.com/zalando-research/fashionmnist

<b> About Practice Problem: </b>

More than 25% of entire revenue in E-Commerce is attributed to apparels & accessories. A major problem they face is categorizing these apparels from just the images especially when the categories provided by the brands are inconsistent. This poses an interesting computer vision problem which has caught the eyes of several deep learning researchers.

We have total 70,000 images (28 x 28), out of which 60,000 are part of train images with the label of the type of apparel (total classes: 10) and rest 10,000 images are unlabelled (known as test images).The task is to identify the type of apparel for all test images. Given below is the code description for each of the apparel class/label.
 
<b> Labels and Descriptions </b>

Label	Description
0	T-shirt/top
1	Trouser
2	Pullover
3	Dress
4	Coat
5	Sandal
6	Shirt
7	Sneaker
8	Bag
9	Ankle boot 

<b> Public-Private Split </b>

Public and Private split for test images are 40:60.

<b> Evaluation Metric </b>

The evaluation metric for this challenge is multi-class accuracy.

<b> Data </b>

Train link has "train.csv" and apparel images for train
Test link has "test.csv" having images name, need to predict the image label
Sample Submissons link has the csv format for the submission file
