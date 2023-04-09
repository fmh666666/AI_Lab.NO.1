# AI_Lab.NO.1

#### 介绍

深度智能实验室第一次题目

---



#### 题目一:图像分类

难度：1

用时：3天

知识点：练习构建基础的网络模型和训练过程

数据集：CIFAR100

使用语言和框架：python和pytorch

要求：使用MLP和CNN模型，对图像进行分类，并尝试使用resnet模型。

输入：32*32*3的图像

输出：类别概率

评价标准：准确率

结果要求：学习并尝试使用各种训练技巧，包括但不限于：标签平滑，数据增强（几何变换、随机调整亮度、随机调整对比度、随机擦除等），尝试对比Adam、SGD两种优化器并比较优劣，使用表格记录各个技巧对模型性能的影响（消融实验）。


---



#### 题目2：简易中文文本分类

难度：2

用时：3天

知识点：理解NLP数据处理和训练预测的基本过程。

数据集：外卖评价数据集waimai_10k，酒店评价数据集ChnSentiCorp_htl_all

获取链接：

[1]

[https://raw.githubusercontent.com/SophonPlus/ChineseNlpCorpus/master/datasets/waimai_10k/waimai_10k.csv](https://raw.githubusercontent.com/SophonPlus/ChineseNlpCorpus/master/datasets/waimai_10k/waimai_10k.csv)

[2]

[https://raw.githubusercontent.com/SophonPlus/ChineseNlpCorpus/master/datasets/ChnSentiCorp_htl_all/ChnSentiCorp_htl_all.csv](https://raw.githubusercontent.com/SophonPlus/ChineseNlpCorpus/master/datasets/waimai_10k/waimai_10k.csv)

[3]

[https://github.com/Embedding/Chinese-Word-Vectors.git]()

[1][2]为数据集,要求每个数据集都使用最后500条正向和最后500条负向作为测试集，其余作为训练集合验证集。

使用语言和框架：python和pytorch

要求：使用DPCNN模型，pytorch中的embedding层随机初始化，对文本进行分类,或者Glove预训练,中文语义库见[3]。

输入：搜狗新闻文本

输出：类别概率

评价标准：准确率

结果要求：学习并尝试使用各种训练技巧，包括但不限于：标签平滑，WarmUp，批标准化，尝试对比Adam、SGD两种优化器并比较优劣，使用表格记录各个技巧对模型性能的影响（消融实验）。
