DEMO设计思路：
    1.上传文件
    2.训练决策树算法
    3.应用决策树算法
说明（2018/02/01）：
    1.上传的文件应包括2个文本文件，其一是要分类对象的属性值以及标签值，值之间以tab
      间隔，标签值后应换行，数据集是二维数组的形式；其二是要分类对象的属性，属性的
      排列顺序必须要与上一文件中的属性值的顺序一一对应！！
      注意：建议用专业的文件管理器生成TXT文本文档，编码格式为utf-8，无BOM，不要使
      用Windows自带的文本文件管理器！！以免出现乱码问题！
    2.点击按钮，即可看到训练结果。
    3.选择对应的属性值，即可应用生成的决策树进行判断！

后期改进(2018/02/02)：
    1.因为前期是按照机器学习实战中的实例代码，同时结合机器学习书本中的西瓜数据，所
      以例子完全是针对西瓜数据集进行处理的，所有的要求最终都是基于西瓜数据提出的。
      这个例子算是第一版，可扩展性很差！
    2.基于上述原因及结论，下一步的工作就是增强本demo的可扩展性；不管是什么物品，
      西瓜、葡萄、苹果等等，收集完物品的属性以及属性值之后，都可以放在本demo中进行
      学习，并且要达到能投入使用的程度。

需求已完成！！
