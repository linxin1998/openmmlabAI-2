# openmmlabAI-2
# 基础实验
openmmlab实战营作业2 作业任务：基于自定义数据集 balloon 训练实例分割模型，基于训练的模型在样例视频上完成color splash的效果制作，即使用模型对图像进行逐帧实例分割，并将气球以外的图像转换为灰度图像。
# 实验设备
NVIDIA GeForce GTX 3090
# 数据集介绍
balloon是带有mask的气球数据集，其中训练集包含61张图片，验证集包含13张图片。
下载链接：https://github.com/matterport/Mask_RCNN/releases/download/v2.1/balloon_dataset.zip
# 实验结果
epoch=10， "bbox_mAP": 0.712
# 进阶作业
使用mmdetection完成项目，使用以下数据集   
目标检测数据集：PASCAL VOC20107：https://opendatalab.org.cn/PASCAL_VOC2007
# 实验设备
NVIDIA GeForce GTX 3090
# 实验结果
epoch=4 "bbox_mAP": 0.7690
