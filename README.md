#### - RDNSR- tf.Keras implementation
image super resolution algorithm 
#### Unofficial implementation of [RDNSR](https://arxiv.org/pdf/1802.08797.pdf)


#### Requirements
* Tensorflow 1.13 <=
* OpenCV
* Albumenations

#### Training in your own data
```
customize the required in the config.py --(EXAMPLE(LEARNING_RATE, TRAIN_IMAGE_COUNT, VAL_IMAGE_COUNT)
customize the dataset path in Train.py

```
#### Note
```
to support dynamic tensors batch size cannot exceed 1.  
```

