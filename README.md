# LVEAD-02460
This repo contains an implementation of the LVEAD algorithm for anomaly detection described in the article [Time Series Anomaly Detection with Variational Autoencoders](https://arxiv.org/pdf/1907.01702.pdf).


## Github repos with examples of VAE for anomaly detection
- [This](https://github.com/KDD-OpenSource/DeepADoTS) repo might just be the most useful. It contains PyTorch implementations of a wide range of time series outlier detection algorithm (e.g. an LSTM based encoder-decoder structure).
- [Here](https://github.com/Danyleb/Variational-Lstm-Autoencoder) is a tensorflow implementation of an LSTM-VAE that is not used for outlier detection. (Danyleb)
- [This](https://github.com/ldeecke/vae-torch) repo has implemented a PyTorch CNN-based VAE to detect outliers in images.
- [Here](https://github.com/SeldonIO/seldon-core/blob/master/components/outlier-detection/vae) is a Keras implementation of an outlier detection VAE with simple dense layers (FNN)
- [This](https://github.com/JGuymont/vae-anomaly-detector) repo has a similar approach to the one above only with a PyTorch implementation instead of Keras.
- [This](https://github.com/DeepLearningDTU/02456-deep-learning-with-PyTorch/blob/master/7_Unsupervised/7.2-EXE-variational-autoencoder.ipynb) repo is the one provided by Tommy on VAE from the deep learning course on DTU.

