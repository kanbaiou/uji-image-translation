### 概要
为了做宇治圣地巡礼的游戏，
现在考虑做一个把宇治的照片转换成京吹风格的项目
考虑基于图片转换的gan技术把图片转换成京吹动画domain的图片

#### TODO

* 收集京吹的图片数据集
  * 图片来源：京吹一二季tv，剧场版总集篇1和2，誓言的终章 bd截屏即可，b站720p以上也可
  * 图片要求：室外景色（街景，自然景色）占主要成分的画面，有少量人物也可以
  * 需要数据数量 1000-2000张之间，越多越好
  * 可供参考的其他类似数据集： https://github.com/TachibanaYoshino/AnimeGANv2/releases/tag/1.0
    * 以新海诚风格图片为例，下载 Shinkai.tar.gz
    * windows：去下载的文件夹打开powershell（shift加右键可选） 执行tar -xvzf Shinkai.tar.gz 解压缩
    * 可以查看数据集里面的内容 目的就是做类似的东西

* 收集宇治风景数据
  * 整理手边的数据

* 确定使用的算法和模型
  * 参考https://github.com/TachibanaYoshino/AnimeGANv2

* 训练

* 根据效果调参和模型调优


