# 计算机科学与编程⼊门课程第一次作业
## 2300092518 何元棋
## 1. 作业1

### part 1
这是一张世界地图，展示了各国公民的国际象棋联合会（FIDE）的总评级。我首先上网获取了所有现有FIDE成员及其评级和国家的CSV文件。由于FIDE使用的是非标准化的国家代码系统，因此我需要将这些代码转换为pyecharts可以使用的国家名称。我通过一个名为“pycountry”的库实现了这一点。然而，由于国家代码系统并非标准的ISO格式，我不得不手动查阅FIDE网站上的代码，将部分代码改为名称。然后，我将每个国家的评级相加并绘制出来。

[作业一链接1](https://szycxn.github.io/testmapchessl.html)

### part 2
这是一张关于中国各城市平均气温的地理时间线图表。它展示了从2012年到2022年的平均温度变化。我使用了散点地理类型来展示每个城市的数据点。图表中的最低点和最高点分别代表了当年最高和最低的平均气温。

[作业一链接2](https://szycxn.github.io/timeline_mapnewone.html)


## 2. 作业2

以下图表展示了美国智能手机用户总数与苹果公司在该年份所占的市场份额之间的关系。它结合了条形图和折线图，并使用不同的坐标轴来更好地说明其观点。

[作业二链接](https://szycxn.github.io/smartphone_grid_chart.html)


## 3. 作业3

我小时候总是把哈利·波特想象成一个勇敢、精明、坚韧的人。因此，我很好奇书中是如何描述他的，是否和我的印象相符。于是，我决定数一数第一本哈利·波特书中形容词出现的次数，以及它们与哈利一起出现的次数，并创建一个词云图来总结这些发现。

具体而言，它实现了以下步骤：

读取指定文本文件并将其分段。

对每个段落进行分词和词性标注，提取出形容词。

统计每个形容词与哈利同行出现的次数。

根据统计结果生成词云图，其中形容词的大小表示其出现的频率。

[作业三链接](https://szycxn.github.io/Figure_1.png)
