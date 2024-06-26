# openai-storytelling-quickstart
## 章节内容生成
```
请根据下面概要，将内容续写成800字的章回制小说

章节名：黄巾起义
概要：
'''
东汉建宁元年（168年）九月，宦官曹节、王甫等人专横，大将军窦武与太傅陈蕃因憎恶而意图除害，不料事迹败露，反被消灭[9]:34。汉桓帝、汉灵帝昏庸无道，宠信宦官，疏远良臣，致使朝政腐败，百姓生活困苦。灵帝时，张角自称曾遇见仙人，幸得天书，学得有效治病方法。后来他云游四方给人治病（他治病的方法带有宗教色彩，但在某些因素的作用下，这使他声名远播），借此聚众起事，欲图推翻东汉，爆发农民大暴动——黄巾起义。

在大将军何进带领军队剿灭了黄巾军之后，又发生了十常侍之乱。这时汉灵帝已故，汉少帝刘辩即位。何进欲杀皇宫里所有宦官，反被宦官诱杀。袁绍和曹操带领众大臣冲入皇宫，杀绝宦官，还误杀不少不留胡须的男人。少帝与陈留王刘协于慌乱中逃出皇宫。
'''
小说：[内容]

```

## 对话内容生成
```
请根据下面章节名、概要、场景，将内容续写成800字的关于三国时期，刘备和曹操的对话

章节名：黄巾起义
概要：
'''
东汉建宁元年（168年）九月，宦官曹节、王甫等人专横，大将军窦武与太傅陈蕃因憎恶而意图除害，不料事迹败露，反被消灭。汉桓帝、汉灵帝昏庸无道，宠信宦官，疏远良臣，致使朝政腐败，百姓生活困苦。灵帝时，张角自称曾遇见仙人，幸得天书，学得有效治病方法。后来他云游四方给人治病（他治病的方法带有宗教色彩，但在某些因素的作用下，这使他声名远播），借此聚众起事，欲图推翻东汉，爆发农民大暴动——黄巾起义。

在大将军何进带领军队剿灭了黄巾军之后，又发生了十常侍之乱。这时汉灵帝已故，汉少帝刘辩即位。何进欲杀皇宫里所有宦官，反被宦官诱杀。袁绍和曹操带领众大臣冲入皇宫，杀绝宦官，还误杀不少不留胡须的男人。少帝与陈留王刘协于慌乱中逃出皇宫。

在一片兵荒马乱之中，曹操遇到了这一生最大的对手，刘备，他们开始了一次对话。
'''
曹操的性格：[内容]
刘备的性格：[内容]
对话内容:[内容]
```

## 生成候选新章节（新方向）
```
请根据下面章节名、概要、场景，请推理出3个不同的发展方向，每个方向都详细描述新的章节名、概要和场景。

章节名：黄巾起义
概要：
'''
东汉建宁元年（168年）九月，宦官曹节、王甫等人专横，大将军窦武与太傅陈蕃因憎恶而意图除害，不料事迹败露，反被消灭。汉桓帝、汉灵帝昏庸无道，宠信宦官，疏远良臣，致使朝政腐败，百姓生活困苦。灵帝时，张角自称曾遇见仙人，幸得天书，学得有效治病方法。后来他云游四方给人治病（他治病的方法带有宗教色彩，但在某些因素的作用下，这使他声名远播），借此聚众起事，欲图推翻东汉，爆发农民大暴动——黄巾起义。

在大将军何进带领军队剿灭了黄巾军之后，又发生了十常侍之乱。这时汉灵帝已故，汉少帝刘辩即位。何进欲杀皇宫里所有宦官，反被宦官诱杀。袁绍和曹操带领众大臣冲入皇宫，杀绝宦官，还误杀不少不留胡须的男人。少帝与陈留王刘协于慌乱中逃出皇宫。

在一片兵荒马乱之中，曹操遇到了这一生最大的对手，刘备，他们开始了一次对话。
'''

方向A：
章节名：[内容]
概要：[内容]
人物a：[内容]
人物b：[内容]

方向B：
章节名：[内容]
概要：[内容]
人物a：[内容]
人物b：[内容]

方向C：
章节名：[内容]
概要：[内容]
人物a：[内容]
人物b：[内容]

```

## 文章摘要
```
你会向我索要一篇文章。然后你会生成越来越简洁、信息密度越来越高的摘要。

重复以下两个步骤5次。

步骤1：从文章中找出1-3个信息实体（用";"分隔），这些实体在之前的摘要中缺失。
步骤2：写一个新的、更密集的摘要，长度相同，但涵盖每个实体和之前摘要中的细节以及缺失的实体。

一个缺失的实体需要：

与主要故事相关，
具体且简洁（不超过5个词），
新颖（之前的摘要中没有），
忠实于文章（出现在文章中），
可以出现在文章的任何地方。
指南：

第一个摘要应较长（4-5句，约80个词），但高度非特定，除了标记为缺失的实体外几乎不包含任何信息。使用过于冗长的语言和填充词（例如，“本文讨论”）达到约80个词。
让每个词都起作用：重写之前的摘要以改善流畅度，并为额外的实体腾出空间。
通过融合、压缩和删除不具信息性的短语（如“本文讨论”）腾出空间。
摘要应变得高度密集和简洁，但自成一体，即无需文章也能轻松理解。
缺失的实体可以出现在新摘要的任何地方。
永远不要删除之前摘要中的实体。如果不能腾出空间，添加较少的新实体。
记住，每个摘要的词数必须相同。
答案以JSON格式回答。JSON应该是一个包含5个字典的列表，每个字典的键是"Missing_Entities"和"Denser_Summary"。
```

## 内容扩写
```
请为我将下面故事拓展成800字的文章，要求符合约瑟夫·坎贝尔（Joseph Campbell）的"千面英雄"（The Hero with a Thousand Faces）大框架

-------
{}
```
