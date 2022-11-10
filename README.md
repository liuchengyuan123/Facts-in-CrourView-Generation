# Facts in CourtView Generation 论文

- Interpretable Charge Predictions for Criminal Cases: Learning to Generate Court Views from Fact Descriptions
  - 针对特定的charge，因此输入中包含一个对charge的编码
  - 使用简单的基于注意力的encoder-decoder结构生成rationale
- C3VG
  - 分开了Adj（与判别罪名相关的部分）与Sec（与判断刑期相关的部分）
  - 两个阶段
    - Extraction：从事实描述中抽取出Adj与Sec
    - Generation：生成对应的rationale
    - 加入一个罪名预测任务，降低Adj部分的噪音
  - 数据集很有价值，规模大
- <font color=red>Explainable legal case matching via inverse optimal transport-based rationale extraction</font>
- How Does NLP Benefit Legal System: A Summary of Legal Artificial Intelligence
  - NLP + Legal 综述
  - 分析了两大类任务
    - 基于符号的任务和方法，主要指生成一个结构化的信息
    - 基于Embedding的方法，指神经网络、预训练等方法，以及法律知识图
  - 分析了三类应用
    - 司法预测
    - 类案匹配
    - 司法问答
- De-biased court's view generation with causality
  - 从因果角度分析了法官生成观点的偏见
  - 基于后门调整改进生成过程
- Iteratively Questioning and Answering for Interpretable Legal Judgment Prediction
  - 基于问答的方式提高LJP任务
  - 手动构造了29个Legal Element
  - 虽然效果没有超过SOTA，但可解释性较好
  - 有错误分析

