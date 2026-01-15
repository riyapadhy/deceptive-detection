Deceptive Spam Review Detection with Convolutional Neural Network in Tensorflow
This code belongs to the "DECEPTIVE SPAM REVIEW DETECTION WITH CNN USING TENSORFLOW" blog post.

We implement a model similar to the SCNN model of Luyang Li's Document representation and feature combination for deceptive spam review detection. In that paper, the SCNN model apply convolutional neural network (CNN) technique to detect deceptive spam review.

A Deceptive opinion spam is a review with fictitious opinions which is deliberately written to sound authentic. Deceptive spam review detection can then be thought as of the exercise of taking a review and determining whether is a spam or a truth.

Requirements
Python 2.7
Jupyter Notebook
Tensorflow
Numpy
Dataset
We use the first publicly available gold standard corpus of deceptive opinion spam. The dataset consists of truthful and deceptive hotel reviews of 20 Chicago hotels. It contains:

400 truthful positive reviews from TripAdvisor
400 deceptive positive reviews from Mechanical Turk
400 truthful negative reviews from Expedia, Hotels.com, Orbitz, Priceline, TripAdvisor and Yelp
400 deceptive negative reviews from Mechanical Turk.
References
Document representation and feature combination for deceptive spam review detection

Implementing a CNN for Text Classification in TensorFlow

Perform sentiment analysis with LSTMs, using TensorFlow
