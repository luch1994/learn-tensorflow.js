# learn-tensorflow.js

本人也是tensorflow.js的初学者，主要记录自己学习的过程，如果帮助到了你，可以给个赞


文件夹 | 描述
-------|-------
server |一个nodejs文件服务器，主要存放一些训练好的模型，然后客户端直接加载模型并且预测
straight-line-fitting | 通过自己定义tensorflow变量的方式进行直线拟合，找出最优的变量
straight-line-fitting-model | 通过定义模型的方式，传入训练的数据和label，训练模型，并使用训练好得模型进行预测，如果预测结果不满意，可进行多次训练，训练好的模型可以保存
straight-line-fitting-model-load | 加载已经训练好的模型，输入点进行预测
mnist-web | tensorflow.js官方的例子，按照理解，使用他的数据源训练模型，并保存
mnist-web-model-load | 使用上一步训练的模型预测结果
polynomial-web | 使用变量的方式进行曲线拟合，使用echarts绘制图表数据