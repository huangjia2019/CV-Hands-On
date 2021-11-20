# 代码说明一览

## SelectiveSearch
原始资料来自于Modern Computer Vision with PyTorch第7章
https://github.com/PacktPublishing/Modern-Computer-Vision-with-PyTorch

## ObjectDectionRCNN 
原始资料来自于Modern Computer Vision with PyTorch第7章
https://github.com/PacktPublishing/Modern-Computer-Vision-with-PyTorch

## WheatDetection 
20211120
    成绩
        1）比较了模型output和target真值的两种选择框差异
        2）研究了迁移学习需要训练几次的问题，2次之后，就有明显效果
    需要解决的问题
        1）输出测试图片显示的绘图效率，要直接选材（不需要Valid Loader），还不能重叠。
        2）根据类别的概率来选择前30个框即可，不需要100个框这么多。 