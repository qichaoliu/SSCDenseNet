# SSCDenseNet
A new network algorithm for HSI classification

Environment requires: GPU >= GTX1080Ti (11GB Memory)

SSCDenseNet：一种空-谱卷积稠密网络的高光谱图像分类算法

SSCDenseNet: A Spectral-Spatial Convolutional Dense Network for Hyperspectral Image Classification

摘要:基于深度学习的高光谱遥感图像地物分类是目前研究的热点。但由于其参数规模大以及结构复杂，深度网络通常需要大量训练样本和较长训练时间，如何在小规模样本下建立深度学习监督分类模型是需要解决的关键问题。本文提出了一种小规模样本下高光谱图像分类的空-谱卷积稠密网络算法，称为SSCDenseNet，其包含三种新颖的架构策略：1）空-谱分离卷积，即采取光谱维一维卷积和空间维二维卷积的分离卷积结构构成隐层单元，并通过多个隐层单元堆叠构造深度网络；2）隐层单元中使用批归一化，减少数据协方差漂移及加速网络训练；3）隐层单元间构建稠密连接，缓解梯度消失问题并实现特征复用。通过Indian Pines、Pavia University与Salinas数据集进行综合测评，表明该方法优于若干最新深度学习方法，特别在小规模样本下具有优异的分类性能。	
关键词 ： 高光谱图像,  监督分类,  深度学习,  稠密网络,  空-谱卷积    

Abstract：Due to the massive parameters and complex structure, deep learning networks are usually trained in a long time with large-scale training samples. In this paper, we propose a spatial-spectral convolutional dense network (SSCDenseNet) which mainly targets limited samples for hyperspectral image classification. Three novel strategies are proposed to construct the proposed network. First, a spatial-spectral separable convolution method is adopted to make up a hidden layer unit with a spectral one-dimensional convolutional layer and a spatial two-dimensional convolutional layer, then the deep network is constructed by stacking multiple units. Second, we use batch normalization before each hidden layer unit to reduce covariance drift of data and accelerate the network training procedure. Finally, a direct connection between every two units is adopted to reuse hierarchical features, and solve the problem of gradient vanishing. The comprehensive evaluation of experiments on different datasets such as Indian Pines, Pavia University and Salinas are conducted to show the performance of the SSCDenseNet, and the results show that the proposed method outperforms several state-of-the-art deep learning based methods in terms of classification performance, especially under small-scale samples.
Key words： hyperspectral image    supervised classification    deep learning    dense network    spectral-spatial convolution   

引用本文:   
刘启超, 肖亮, 刘芳, 徐金环. SSCDenseNet:一种空-谱卷积稠密网络的高光谱图像分类算法[J]. 电子学报, 2020, 48(4): 751-762. LIU Qi-chao, XIAO Liang, LIU Fang, XU Jin-huan. SSCDenseNet:A Spectral-Spatial Convolutional Dense Network for Hyperspectral Image Classification. Acta Electronica Sinica, 2020, 48(4): 751-762.

链接本文:  
http://www.ejournal.org.cn/CN/10.3969/j.issn.0372-2112.2020.04.017     或     http://www.ejournal.org.cn/CN/Y2020/V48/I4/751
