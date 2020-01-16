# Labels for COCO and ImageNet

The file [coco/labels-2014_2017.txt](coco/labels-2014_2017.txt) contains
human-readable labels for the 80 [COCO][COCO] classes.

The file [coco/labels-paper.txt](coco/labels-paper.txt) contains
human-readable labels for the 91 [COCO][COCO] classes used in original coco paper.

For more details one can follow below article.
https://tech.amikelive.com/node-718/what-object-categories-labels-are-in-coco-dataset/


[Keras][Keras] [uses][keras-imagenet-utils] this
  [data](imagenet/class_index.json) for its human-readable labels. The labels consist of the
  first synonym from each synset (with spaces replaced with underscores).


## License

Public domain.

[COCO]:  http://cocodataset.org/
[Keras]: https://keras.io/
[keras-imagenet-utils]: https://github.com/keras-team/keras-applications/blob/master/keras_applications/imagenet_utils.py
