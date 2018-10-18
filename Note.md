# Person Re-Idetification

## 关于数据集

### VIReP

参考：<https://vision.soe.ucsc.edu/%20?q=node/178>

VIRep (Viewport Invariant Pedestrian Recognition): Contains 632 pedestrian image pairs, taken from arbitrary viewpoints under varying illumination conditions.

632 对在两个摄像头下对同一个行人所拍摄的图片，每张图片大小是 128×48 个像素。

下载之后的文件组织结构为：
```
├── README.txt
├── cam_a
│   ├── 000_45.bmp
│   ├── 001_45.bmp
│   ├── ...
│   ├── 872_0.bmp
│   └── 873_0.bmp
└── cam_b
    ├── 000_45.bmp
    ├── 001_90.bmp
    ├── ...
    ├── 872_180.bmp
    └── 873_180.bmp
```
上面的图片为：
![](./data/VIPeR/cam_a/000_45.bmp) ![](./data/VIPeR/cam_b/000_45.bmp) ![](./data/VIPeR/cam_a/001_45.bmp) ![](./data/VIPeR/cam_b/001_90.bmp) ![](./data/VIPeR/cam_a/872_0.bmp) ![](./data/VIPeR/cam_b/872_180.bmp) ![](./data/VIPeR/cam_a/873_0.bmp) ![](./data/VIPeR/cam_b/873_180.bmp)

其中编号为 247~299, 349, 352, 356, 363, 396~499, 530, 559, 586, 602, 644, 663, 665, 668, 681, 688, 691, 694~695, 704, 710, 712, 718~719, 727, 730, 739, 742~799, 810, 857 图片不存在。

####  VIPeR 评价标准

[Evaluating Appearance Models for Recognition, Reacquisition, and Tracking](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.331.7285&rep=rep1&type=pdf)

