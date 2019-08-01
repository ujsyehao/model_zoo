# classification model 
### lightweight 
* tiny-fire model: top-1 accuracy-49.974% -> 51.10% 
* squeezenet
* mobilenet v1
* peleenet
* IGCV 1
* Nasnet
* shufflenet v1
* mobilenet v2
* IGCV 2
* shufflenet v2
* IGCV 3
* mobilenet v3
* xception



### heavy
* VGG
* resnet
* densenet
* highway network
* SE-Net
* Inception v3, v4
* EfficientNet
* Hrnet

## Table
| network            | top-1 accuracy    |  params(million)  | flops/Madds(million) | latency(ms)-hardware |
| --------           | -----:            | :----:            | :-----:              | :-------:            |
| fire(tiny ssd)     | 48.8              |                   |                      |                      |
| alexnet            |  57.2             |   60              |    720               |                      |
| squeezenet v1      | 57.5              |   1.25            |  1700                |                      |
| mobilenet v2 0.35  |        60.8   | 1.6 | 59.2 |   |
| squeezenet v1-variant | 61 |  |  |  | 
| shufflenetv2 0.5 | 60.3 | | 41 | |
| mobilenetv1 0.5 | 63.7 | 1.3 | 149| |
| mnasnet | 64.9 | 1.9 | 65.1 | |
| mobilenetv3-small 0.75 | 65.4 | 2.4 | 44 | |
| mobilenetv1 160x160 | 67.2 | 4.2 | 290 | | 
| mobilenetv3-small 1.0 | 67.4 | 2.9 | 66 | |
| mobilenetv1 0.75 | 68.4 | 2.6 | 325 | |
| mobilenetv1 192x192 | 69.1 | 4.2 | 418 | |
| shufflenetv2 | 69.4 |  | 146 | |
| googlenet| 69.8 | 6.8 | 1550 | |
| mobilenetv1 | 70.6 | 4.24 | 575 | |
| peleenet| 71.3 | 2.8 | 508 | |
| VGG16 | 71.5 | 138 | 15346| |
| shufflenetv1 1.5x | 71.5 | 3.4 | 292 | |
| mobilenetv2 | 72 | 3.4 | 300 | P1-78 P2-90 P3-61.3 |
| mobilenetv3-large 0.75 | 73.3 | 4 | 155 | |
| shufflenetv1 2x(g=3) | 73.7 | 5.2 | 524 | |
| inception v2 | 73.9 |  | | |
| Nasnet-A | 74 | 5.3 | 564 | |
| shufflenetv1 | 74.8 | | 2300| | 
| shufflenetv2 2x | 74.9 | | 591 | |
| densenet-41-variant| 75.0 | 1.13 | 545 | |
| mobilenetv3-large | 75.2 | 5.4 | 219 | P1-66 P2-77 P3-52.6|
| mnasnet-A1 | 75.2 | 3.9 | 315 | |
| resnet50 | 76 | 26 | 4100| |
| densenet169 | 76.2 | 14 | 3500 | |
| efficientnetB0 | 76.3 | 5.3 | 390




# detection model
