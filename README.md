# osrs-iron-cnn
---

A object detector for iron ores in the popular game Runescape that I developed with Python using TensorFlow. I trained a convolutional neural network object detection classifier for multiple objects using the Faster-RCNN COCO model to detect both iron rock and depleted iron rock objects within the game. This tool can be used to create a bot that automates some of the most repetitive content (mining) in the game.

I used this model: 
https://github.com/navroopsingh1/osrs-iron-data-set
I used my own data-set that you can download here: http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz

### Two non-training set images
![Original](demo/DEMO1.png)
![Recreated](demo/DEMO2.png)