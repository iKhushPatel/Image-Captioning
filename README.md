# Image Captioning Project
## Introduction
The repository contains a neural network, which can automatically generate captions from images. 

## Network Architecture
The solution architecture consists of:
1. CNN encoder, which encodes the images into the embedded feature vectors:
<p align="center">
  <img src="./assets/encoder.png" width=50% height=50% />
</p>
2. Decoder, which is a sequential neural network consisting of LSTM units, which translates the feature vector into a sequence of tokens:
<p align="center">
  <img src="./assets/decoder.png" width=50% height=50% />
</p>

## Results
These are some of the outputs give by the network using the [COCO dataset](http://cocodataset.org/):
<p align="center">
  <img src="./assets/example1.png" width=50% height=50% />
</p>
<p align="center">
  <img src="./assets/example2.png" width=50% height=50% />
</p>
