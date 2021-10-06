关于该项目的原理，可以参考[GAN网络之入门教程（五）之基于条件cGAN动漫头像生成](https://www.cnblogs.com/xiaohuiduan/p/13791700.html)

关于更多GAN网络的原理，可以参考[GAN网络入门](https://www.cnblogs.com/xiaohuiduan/category/1799415.html)

关于用网页的形式展示该项目，可以参考项目[cgan_web](https://github.com/xiaohuiduan/cgan_web)
![](https://user-images.githubusercontent.com/40485068/135795600-f9b3f743-346b-404a-a254-7401db7b8b66.png)

### 运行环境

- keras：2.2.0
- tensorflow：1.14.0 ：下载地址https://github.com/mind/wheels/releases/tag/tf1.4-cpu
- python：3.5.6

### 目的

使用条件GAN网络，根据标签生成个性化的图片，如下图所示：

1.  ![](readme_img/1.png)

改变选项后生成图片如下所示：
2.  ![](readme_img/2.png)

### 文件介绍

1. faces 文件夹☞数据集
2. generate_img 文件夹☞训练过程产生的图片
3. model 文件夹☞训练好的模型
4. main.ipynb ☞ 训练代码 
5. gui.py ☞ gui代码
6. tags_clean.csv 图片标签数据


### 参考

- [Anime-Face-ACGAN](https://github.com/CryoliteZ/Anime-Face-ACGAN)

- [GAN网络入门](https://www.cnblogs.com/xiaohuiduan/category/1799415.html)

