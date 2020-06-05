# [排行榜](https://tianchi.aliyun.com/competition/entrance/231659/rankingList)

#### 获奖统计(不全)

1. [gogogo-in house-0.67](https://github.com/Brook-Lan/fddc02_intro/tree/master/%E7%AD%94%E8%BE%A9)

   GOGOGO团队把不同公告的问题找到了一些共性的知识结构，能快速把复杂问题降维。另外，通过章节的识别提升效率。评委表示，该团队作品中，对html的结构运用处理理念和效果较好。

   抽取模型的关键是关系建立，包括主键组合，即同一个句子中的实体组合主键；同性关联主键，即主键与属性出现在同一个句子的组合；条件规则过滤，即关键词匹配句子过滤；去重等:

   i. 他们首先是对HTML结构的提取，包括一些数据清理和转换、表格识别等。

   ii. 在算法中，团队运用了反向标注，然后建立一个NER的模型预测实体。GOGOGO的标注不同之处在于，他们做了直接的实体的全量标注。因为现有的很多通用的实体识别，是识别出一个公司名称或者是不是数值，团队直接把它的类型给定义清楚。
   实体标注技巧是模型里面比较重要的地方之一，另一方面，团队还用到奥卡姆剃刀原则。
       奥卡姆剃刀原则主要表现在人倾向于用一个简单的方法表现一个内容，会用简单的方法不会用复杂的方法。比如，有很多合同里面没有乙方的表示，默认发公告的一方就是乙方。

   iii. 模型验证策略方面，团队在研究这个问题的时候，发现召回率是很重要的，信息一旦漏掉了是捞不回来的，因此可以通过人工的方法提高它。第二是模型效率的问题，因为用到很多抽象的方法，很多情况下并没有通篇读，所以速度非常高，基本上控制在秒级。整个过程中大部分时间还是在实体识别里面。

2. Heisenberg-南京大学-0.66

   Heisenberg团队有两个亮点：1、有实用价值的系统架构，能很快用到工业界。2、在实体识别的方法比传统的有很大提升。

3. [Miyabi](https://github.com/Brook-Lan/fddc02_intro/tree/master/%E7%AD%94%E8%BE%A9)

   通联数据CEO王政点评:"Miyabi团队用表格和分类的方法来抽取，能够快速抽取结果；分类的方法能判断哪些可以抽取。"

   李灏舟:"使用了细致和全面的文本处理方法，也设计了一整套完整的抽取方案，同时通过fastText来增加信噪比，加速了整体系统的运行时间，通过各种模型比对和优化方法得到了效率较高、扩展性较强的方案" 
   冯霁:"基于数据驱动跟规则驱动结合的解决方案，很有可能比较高效的把问题进行比较好的解决。第一是进行HTML解析，然后进行实体命名识别，基于关系抽取定义了一套规则，把它进行事件抽取，然后再进行事件合并"

4. [智能ABC-浙江大学-0.59](https://github.com/mrgjbd/fddc02)



- 最具创意极客奖：东风又绿江南岸团队，智能ABC团队；

- 最具潜力极客奖：KingofWind团队，ASD123团队；



8. [填写团队名称-上海中和软件有限公司](https://github.com/magicdict/FDDC)



- [chouisbo 贡献的demo](https://github.com/dmjvictory/fddc-extraction-release)

  先从HTML中进行简单的抽取，然后使用规则分别针对 表格 和 正文进行增减持信息抽取，期间还用到了 NER 相关技术进行一些实体标注，最后做了一些格式规范化



#### 团队介绍

- GOGOGO团队：黄泽炽([优秀硕士论文](http://gb.oversea.cnki.net/KCMS/detail/detail.aspx?filename=1012437729.nh&dbcode=CMFD&dbname=CMFD2012))，毕业于湖南师范大学，生物化学与分子生物学专业。
- Heisenberg团队：冯霁([个人简历](http://www.lamda.nju.edu.cn/fengj/
  ))，现就读于南京大学，计算机科学与技术专业；李永刚，现就读于山东大学；苏洋洋，现就读于山东大学，软件工程专业。
- Miyabi团队：李灏舟([人人](http://www.renren.com/418318714/profile)[领英](https://www.linkedin.com/in/%E7%81%8F%E8%88%9F-%E6%9D%8E-18b782aa/)[脉脉](https://maimai.cn/contact/detail/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1IjozNjQ2MjExNSwidCI6ImN0dCIsImxldmVsIjowfQ.NQpmky-gZZBFhCH5dFt68QtFIUT9cainHIx-taumfyg?fr=&from=webview%23%2Ffeed_list))  毕业于北京邮电大学，信息与通信工程专业；王夺  毕业于北京邮电大学，物理学专业；丛冠男  现就读于北京邮电大学，计算机技术专业；胡一川  现就读于北京邮电大学，信息与通信工程专业。
- 东风又绿江南岸团队：林建生 现就读于韶关学院，物理学专业；宋云生 毕业于中山大学，统计学专业；宫保伟 毕业于延边大学，统计学专业；林刚 现就读于广东工业大学，机械电子专业。
- 智能ABC团队：周武洁 现就读于浙江大学 ，数学与应用数学专业；郭炫志 毕业于西安交通大学，信息与计算科学专业。
- KingofWind团队：李立 毕业于武汉大学，计算机科学与技术专业。
- ASD123团队：肖艳清；杨舰



#### 答辩视频

- 百度网盘(链接:https://pan.baidu.com/s/12oBPPF2cZ4Zeeax1GZEM5g  密码:sek9)
