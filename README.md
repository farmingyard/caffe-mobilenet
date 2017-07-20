# caffe-mobilenet
A caffe implementation of mobilenet's depthwise conv layer from sp2823(https://github.com/BVLC/caffe/pull/5665/files).

# Pretrained mobilenet_1by2 model on ImageNet
This net structure is same to shicai's mobilenet(https://github.com/shicai/MobileNet-Caffe), but all layers have half filters. 
The top-1/5 accuracy rates by using single center crop (crop size: 224x224, image size: 256x256):

Network|Top-1|Top-5|Download|Architecture
:---:|:---:|:---:|:---:|:---:
MobileNet| 62.0%| 84.1%| [caffemodel (5.1 MB)](http://pan.baidu.com/s/1kUM0WPx)| [deploy](https://github.com/farmingyard/caffe-mobilenet/blob/master/mobilenet_1by2_deploy.prototxt)
