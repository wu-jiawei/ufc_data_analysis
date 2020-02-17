# ufc_data_analysis
[UFC](www.ufc.cn)(Ultimate Fighting Championship)是世界上最顶级规模最大的mma赛事。（ufc stat）[http://ufcstats.com/statistics/events/completed]网站上记录了UFC从1993年创办
以来的每一场比赛的数据，也包含每个曾参加过UFC比赛的运动员的个人数据。
本项目从(ufc stat)[ufcstats.com]网站上爬取这些数据，并对数据进行清洗， 处理， 分析，探索， 最后将每场比赛之前的数据汇总，得到一行数据。对这些数据
进行建模，利用数据挖掘技术来学习利用历史数据预测红角选手在各场比赛中获胜的概率。项目的各文件说明如下：
* data_analysis_EDA_FE.ipynb是对数据进行清洗，分析，探索，和特征工程的。
* preprocessing_analysis_EDA.ipynb继续进行前面的工作
* FE_modling.ipynb对准备好的数据进行建模，学习，和预测。
* ufc_data文件夹中包含原始数据和各部分处理好的数据。
