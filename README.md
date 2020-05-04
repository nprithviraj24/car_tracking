# Deep Sort for detecting and tracking Cars.

Thanks to [ZQPei](https://github.com/ZQPei/deep_sort_pytorch) for implemeting Deep Sort in PyTorch.

For installation and setup, please follow the official [repository](https://github.com/ZQPei/deep_sort_pytorch)

## Introduction
This is an implement of MOT tracking algorithm deep sort. Deep sort is basicly the 
same with sort but added a CNN model to extract features in image of human part bounded by a
 detector. This CNN model is indeed a RE-ID model and the detector used in 
 [PAPER](https://arxiv.org/abs/1703.07402) is FasterRCNN , and the original source code is
  [HERE](https://github.com/nwojke/deep_sort).  

I have modified the original code to run it on cars.


## References
- paper: [Simple Online and Realtime Tracking with a Deep Association Metric](https://arxiv.org/abs/1703.07402)

- code: [nwojke/deep_sort](https://github.com/nwojke/deep_sort), [ZQPei/deep_sort_pytorch](https://github.com/ZQPei/deep_sort_pytorch)

- paper: [YOLOv3](https://pjreddie.com/media/files/papers/YOLOv3.pdf)

- code: [Joseph Redmon/yolov3](https://pjreddie.com/darknet/yolo/)


### Experiment

I tried it on Youtube video. Following is the small GIF from the video.

I made GIF using VLC and GIMP.


![](./demo/from_youtube.gif)