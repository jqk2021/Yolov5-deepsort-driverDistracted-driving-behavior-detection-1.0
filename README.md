# 人物专注性检测

## 项目快速预览

![快速预览](images/1620298460804.gif?raw=true"快速预览")
## 1.0版本
在征得原作者的同意之后，进行了部分修改，得到V1.0版本

主要不同地方为：

1、疲劳检测中去掉了点头行为的检测，仅保留闭眼检测和打哈欠检测。

2、Yolov5的权重进行了重新训练，增加了训练轮次。

3、前端UI进行了修改，精简了部分功能。

## 项目介绍
该项目为人物专注性检测，分为两个检测部分，疲劳检测和分心行为检测。
疲劳检测部分，使用Dlib进行人脸关键点检测，然后通过计算眼睛和嘴巴的开合程度来判断是存在否闭眼或者打哈欠，并使用Perclos模型计算疲劳程度。
分心行为检测部分，使用Yolov5，检测是否存在玩手机、抽烟、喝水这三种行为。

## 使用方法
依赖：YoloV5、Dlib、PySide2

直接运行main.py，即可使用本程序，具体效果可以观看演示视频。

[bilibili在线观看](https://www.bilibili.com/video/BV1MK4y1d7a8/)

各函数的信息，均在代码中写好了注释，如有疑问请联系1647790440@qq.com

## 致谢
十分感谢原作者的支持和帮助，本项目很大部分都基于源项目，项目所使用的数据集也由原作者提

供。
