# Cust-cg-pai-DataSheet 理工计算机科研平台使用手册
0.前置基础——
	0.1linux操作系统使用，操作系统，配置，文件读写
	0.2集成开发环境jupyter notebook 使用方法，熟练在自己电脑本机数量运行，并可以调试python 程序。
	0.3python 语言基本语法，与基本数据结构，程序调用流程，工程模块化封装
	0.4熟悉任意一个深度学习框架，tensorflow，pytorch，keras等基本使用,熟悉神经网络的模配置与搭建，模型训练，调优，测试过程。
	0.5本机python 环境配置（由于云端只提供了jupyter notebook，推荐本机也使用jupyter notebook）
	0.6docker 虚拟隔离环境——资源容器化
1.申请资源
 
 ![img0](https://raw.githubusercontent.com/yuxiashu/Cust-cg-pai-DataSheet/main/img/t0.png)



2.资源分配成功（若分配不成功，返回1重新申请）
 
![img1](https://raw.githubusercontent.com/yuxiashu/Cust-cg-pai-DataSheet/main/img/t1.png)


3. 查看当前环境与GPU是否可以使用(熟悉linux命令与命令解释语句)
 
![img22](https://raw.githubusercontent.com/yuxiashu/Cust-cg-pai-DataSheet/main/img/t2.png)
4. 熟悉云端Jupyter Notebook开发环境
5.根据自己项目工程需要，定制工程文件夹
![img3](https://raw.githubusercontent.com/yuxiashu/Cust-cg-pai-DataSheet/main/img/t3.png)
 


6.工程运行
## How to use
### Install
```
pip3 install -r requirements.txt
```


### Train
    ```
    python3 mnist_backward.py 
    ```  
训练样例：
 

### Demo
- Download the pretrained model from ()
- Run
```
python3 mnist_app.py 
```  
运行时标准化输入：
input the number of test pictures: 9  ######为测试9张图片，图片存放于fc3/pic  

the path of test picture:pic/0.png   ######测试图片路径/path/to/your/test/images/dir
标准化输出：
the prediction number is : []



