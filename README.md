# 基于Faster R-CNN的安全帽目标检测

本文参考：https://github.com/DataXujing/Faster-R-CNN-Keras 并在此基础上加以改进

数据集下载地址：https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection/data 将其放到./data文件夹下解压

hdf5文件下载地址：链接：https://pan.baidu.com/s/1Eo1EOaosPRqVHWQDuHqvlw 提取码：h1g2 将其放到./config文件夹下

预训练模型下载地址：https://pan.baidu.com/s/1jnqfGMGBm9u958SVjAg_gA 提取码：jpca 将其放到./pre_train文件夹下

使用版本：  

Python==3.6.13  

keras==2.2.0  

tensorflow==1.9.0  

opencv-python==4.3.0.38

(使用更高版本可能导致引用时报错，建议在conda新建一个环境)

hdf5文件和数据集仅供参考，可以将其替换成自己的。
