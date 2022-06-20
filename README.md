# trafficlightdetection
Prerequisites:
1. Download Bosch Small Traffic Light Dataset 
1. install library Tensorflow 
2. Download pretrained Weight Faster R-CNN ResNet 50 Coco


Usage:
Run in this order:

1. to_tfrecords.py
2. train.py (library tensorflow)
3. model_freezer.py 
4. video2image (video to image sequence)
5. inference.py (result for model)
6. objec_detection_video.py (for testing your model) 
