# wodecangku
Java experiment

# 阅读程序

## 实验目的
用类描述计算机中CPU的速度和硬盘容量。

## 实验方法
1.阅读书上例子7-9。
2.用eclipse进行编程。
3.上传至github并撰写报告。

## 实验过程
1.创建project，并在其下创建package，在package下创建CPU、PC、Test、HArdDisk四个class，根据需求分别将四个功能写入。
2.将Test作为主类，在其中进行其他类形参和实参的对应和输出。
3.在main方法中创建一个CPU对象cpu，cpu将自己的speed设置为2200。
4.在main方法中创建一个HardDisk对象disk，disk将自己的amount设置为200。

## 核心方法
1.首先进行框架设计，在Test主类下有CPU、HardDisk、PC三个分类，主类从分类调取参数并设计和调用显示函数show ()从而达到显示CPU速度以及硬盘容量的目的。
2.创建项目Experiment,并创建包one,在此包下进行类的创建和编写。
3.创建CPU 1类，创建参数speed,并创建方法getSpeed,用于之后为speed赋值。
4.创建HardDisk. 1类，创建参数amonut, 并创建方法getAmount,用于之后为amount斌值。
5.创建PC类，创建属性cpu和HD，并创建方法getCPU、getHar dDisk,为属性赋值，并创建显示函数show ()，在函数中利用打印函数对最终的cpu速度和硬盘容童进行显6.最后创建主类Test,首先将Test类里设置主函数，调用上述三类中的函数，并为其赋值、和显示。
6.用Eclipse进行源代码的编译和调试，最后运行出结果。
7.用Gitnub来写报告并提交上传。
## 实验结果
硬盘的容量200，cpu的速度2200。

## 实验感想
熟悉实验Github写报告并提交。了解project，package，class的层次和创建对象的方式。
