# Random-roll-call
Java学习中的小项目：随机点名器

### 项目介绍

随机点名器，即在全班同学中随机的打印出一名同学名字。

要做的随机点名器，它具备以下3个内容：

- 存储所有同学姓名
- 总览全班同学姓名
- 随机点名其中一人，打印到控制台

### 需求分析

在全班同学中随机的打印出一名同学名字。

我们对本项目进行分析，得出如下分析结果：

- 存储全班同学名字
- 打印全班同学每一个人的名字
- 在班级总人数范围内，随机产生一个随机数，查找该随机数所对应的同学名字

在存储同学姓名时，如果对每一个同学都定义一个变量进行姓名存储，则会出现过多孤立的变量，很难一次性将全部数据持有。此时，我们可以使用数组解决多个数据的存储问题。