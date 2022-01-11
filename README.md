# MVCNN_images
A datasets collected from ModelNet40  
本数据集使用blender在ModelNet40模型数据集上采用不同方式采集得到，共包含40种模型，12311个模型，具体如下：  
## 文件结构
    ModelNet40
    ├─airplane
    │  ├─test
    │  └─train
    ├─bathtub
    │  ├─test
    │  └─train
    ├...
    └─xbox
        ├─test
        └─train
## 采集方式一
对每个模型绕着轴心每隔30°采集一张图片，一个模型共采集12张图片。  
## 采集方式二  
对每个模型取上下左右前后共六个视点，对每个视点取上下左右偏30°五张图片，每个模型30张图片。  

## Reference  
A Deeper Look at 3D Shape Classifiers  
Jong-Chyi Su, Matheus Gadelha, Rui Wang, and Subhransu Maji  
Second Workshop on 3D Reconstruction Meets Semantics, ECCV, 2018  

Multi-view Convolutional Neural Networks for 3D Shape Recognition  
Hang Su, Subhransu Maji, Evangelos Kalogerakis, and Erik Learned-Miller,  
International Conference on Computer Vision, ICCV, 2015  
  
如需要完整数据集或者存在版权问题，请联系：574371242@qq.com
