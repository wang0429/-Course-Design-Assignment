#README


###**项目名称**：基于贝叶斯的中文垃圾邮件检测实现

### **项目简介**：
运用来自互联网不同渠道的一万多条中文邮件数据集，并选取Java程序语言，对朴素贝叶斯算法与自然语言处理(NLP)的基本原理进行了阐述，并将其应用于垃圾邮件检测与分类研究。

### **项目运行环境**：


- 实验设备：联想笔记本电脑


- 实验环境：windows10+8GB内存+64位操作系统


- 实验软件：eclipse
 

- 编程语言：java


###**源码目录结构**：

* 暂略
	    

###**系统流程**



1. 文本预处理
	

	1.1 在本模型中对数据集标记了两种标签，spam是垃圾邮件,ham是正常邮件，便于比较该模型在垃圾邮件识别上的好坏。
	

	1.2. 对空格以及非中文字符以及空格进行了过滤处理，使得进入模型参与训练的数据都是中文文本。

2. 基于词典方法的文本分词
3. 文本分类模型：朴素贝叶斯算法



### **项目的一些问题**
1. 待更新


### **关于版权**
1. 本系统是为了学习人工智能领域——自然语言处理内含的设计思想和原理所创建，仅供学习交流使用。
2. 作者初学者，欢迎指教学习。