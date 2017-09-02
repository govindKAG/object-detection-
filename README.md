# Object Detection using TensorFlow

A small set of scripts for real time object detection using tensorFlow's object detection API and openCV in python 3\. It is based on the ipython notebook published along withe the tensorFlow object detection api. It implements the COCO model on video streamed from the webcam.

## Details

- Currently uses the COCO model. (I am training a model of my own but that has not yet been checked in)
- If yo have a good GPU this should run in the high 20fps or more, on my laptop it runs at about 10fps.
- Hardware compatibility is a nightmare, this was tested on my macbook pro running el capitan.

## Requirements

- openCV
- TensorFlow
- Pillow
- Jupyter
- Pillow
- lxml

and all other transitive dependencies

This also uses the protobuf (protocol buffer) compiler by google to compile the object detection model from TensorFlow.
