## TinySSD

## 一、环境和下载

Python>=3.8

CUDA>=11.6

### 1.环境配置

使用anaconda配置环境

将environment.yml文件放置在工作目录下，运行

```
conda env create -f environment.yml
```



### 2.下载代码

```
git clone https://github.com/mushan-sysu/TinySSD
```



## 二、数据集制作

文件中的detection已经包含了处理好的数据。

如果想要训练自己的数据集，就替换background文件夹和target文件夹中的图片，然后运行create_train即可。





## 三、模型的训练

文件中已给出训练好的模型，如果不想训练可以直接使用已经训练好的模型。

更改train.py中的batch_size和epoch运行可直接训练，训练好的结果放在trainres中。



## 四、模型的测试

在修改运行test存放地址与模型参数地址后运行test.py

文件中给出的test.py可直接运行

预训练模型存放在trainres中



## 五、测试结果

测试的结果存放在result中，下面给出检测的效果

![1667201393101](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\1667201393101.png)



![1667201421411](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\1667201421411.png)

