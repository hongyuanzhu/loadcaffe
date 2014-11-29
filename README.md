loadcaffe
=========

Load Caffe networks in Torch7

There is no Caffe dependency, only protobuf has to be installed.

Work in progress! To load a network do:

```lua
require 'loadcaffe'

model = loadcaffe.load('deploy.prototxt', 'bvlc_alexnet.caffemodel', 'ccn2')
```

Tested with cuda-convnet2:

* bvlc_reference_rcnn_ilsvrc13
* bvlc_reference_caffenet
* bvlc_alexnet
* finetune_flickr_style

https://github.com/BVLC/caffe/wiki/Model-Zoo in plans.
