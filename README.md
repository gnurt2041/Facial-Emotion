# Facial Emotion Detection using CNN
The objective of the project is to detect facial expression using image dataset. Convolutional Neural Network is used to classify the images. The output class consists of 7 different types namely angry, disgust, fear, happy, neutral, sad, surprise.

# Dataset Information

The training archive contains 7 different type of human emotions

<img align='center' src="https://github.com/gnurt2041/Facial-Emotion/blob/main/images/1-Figure1-1.png" width="700">

**Dataset link:** https://www.kaggle.com/datasets/aadityasinghal/facial-expression-dataset

**Environment:** Google Colab

**The directory structure:**
```
Facial-Emotions-Detection/
	├── train/
        ├── train/
        │   ├── angry/
        │   ├── disgust/
        │       ├── Training_10371709.jpg
        │       ├── Training_10598340.jpg
        │   ├── :
        │   ├── surprise/ 
        └── test/
main/
	└── facial_emotions_detection.ipynb
```
# Libraries

<li>pandas
<li>numpy
<li>matplotlib
<li>seaborn
<li>keras
<li>tensorflow
<li>scikit-learn
<li>japanize-matplotlib

# Neural Network

<li>CNN Architecture

<h2><img align='center' src="https://github.com/gnurt2041/Facial-Emotion/blob/main/images/plotcnn.png" width="700"><h2>

# Result
<img align='center' src="https://github.com/gnurt2041/Facial-Emotion/blob/main/images/predict.jpg" width="700">

**Accuracy:** ~63.2% 
