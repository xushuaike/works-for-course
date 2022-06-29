# works-for-course
基于多种优化模型的心脏病预测实现  
  -数据集：研究对象选取Kaggle网站中UCI机器学习数据库中的克里夫兰心脏病的相关数据集  
  -模型概括：针对所选取的数据集，考虑血管，血压，血糖，心率，运动时的身体状态等指 标的影响，分别应用逻辑回归算法, K-近邻算法（KNN）,支持向量机(SVM),朴素贝 叶斯,决策树，随机森林及卷积神经网络（CNN）的构建方法，以是否患病为预测目 标建立心脏病诊断分类器,并以所得结果的分类准确度（“accuracy”）为评价指 标结合混淆矩阵可视化对上述所有分类器进行对比分析,从而选出解决问题的最优 化分类器。  
  此外，对除基于 K-近邻算法、朴素贝叶斯和卷积神经网络的分类器外的其他分 类器的参数进行网格搜索（GridSearch）从而确保模型评估时传入的是最优参数, 从而达到高效协助对病情精准诊断的目标。
