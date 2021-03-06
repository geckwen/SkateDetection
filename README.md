# AI-Studio-2021 CCF BDCI基于飞桨实现花样滑冰选手骨骼点动作识别-第6名方案


## 项目描述
人体运动分析是近几年许多领域研究的热点问题。在学科的交叉研究上，人体运动分析涉及到计算机科学、运动人体科学、环境行为学和材料科学等。随着研究的深入以及计算机视觉、5G通信的飞速发展，人体运动分析技术已应用于自动驾驶、影视创作、安防异常事件监测和体育竞技分析、康复等实际场景人体运动分析已成为人工智能领域研究的前沿课题。目前的研究数据普遍缺少细粒度语义信息，导致现存的分割或识别任务缺少时空细粒度动作语义模型。此类研究在竞技体育、运动康复、日常健身等方面有非常重大的意义。相比于图片的细粒度研究，时空细粒度语义的人体动作具有动作的类内方差大、类间方差小这一特点，这将导致由细粒度语义产生的一系列问题，利用粗粒度语义的识别模型进行学习难得获得理想的结果。

基于实际需求以及图深度学习模型的发展，本比赛旨在构建基于骨骼点的细粒度人体动作识别方法。通过本赛题建立精度高、细粒度意义明确的动作识别模型，希望大家探索时空细粒度模型的新方法。


## RES2CTR-GCN介绍
整体结构
本算法是基于CTR-GCN进行改进，采用多流同结构算法整体框架如下图所示：

本模型采用三流形式类似于下列双流的形式

## 双流算法流程图
![image](https://github.com/geckwen/SkateDetection/blob/main/multi_stream.png)

## 单流算法流程图
![image](https://github.com/geckwen/SkateDetection/blob/main/model.png)

## RES2CTR-GCN模块
![image](https://github.com/geckwen/SkateDetection/blob/main/RES2CTR-GCN.png)
![image](https://github.com/geckwen/SkateDetection/blob/main/CTR-GC.png)
![image](https://github.com/geckwen/SkateDetection/blob/main/TEMORAL_MODELING.png)
