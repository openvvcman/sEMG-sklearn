# sEMG-sklearn workflow
1. sEMG原始信号采集：采集--放大--滤波
2. sEMG信号预处理：将处理好的模拟信号通过MCU模数转换成数字信号
3. 特征提取：通过数字信号使用科学计算库提取sEMG信号的一些特征物理量
4. 模型训练：通过提取的特征物理量的数据集，通过机器学习算法（SVM，KNN，随机森林等）将这些特征物理量的值分类，分为几大类映射到手势
5. 控制设备：通过映射的手势传入运动指令，使用控制算法控制设备

***

***2024.10.24***

加入sEMG信号的开源数据集
