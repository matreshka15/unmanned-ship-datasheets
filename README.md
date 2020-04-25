# unmanned-ship-datasheets
开发无人船过程中参考的传感器手册以及算法资料
## 文档说明
* algorithm文件夹内存放无人船涉及的算法资料
  * madgwick_internal_report_withMarginNotes.pdf 为姿态控制算法，即Madgwick的梯度下降算法，强烈推荐
* sensors-datasheet文件夹内存放传感器的说明书与使用手册
  * GPS文件夹内存放编写GPS部分代码使用的手册
  * IMU文件夹内存放IMU模块的手册，包括HMC5883磁力计模块与MPU6050模块
## 文档涉及以下几个Repo
* [下位机端Github地址](https://github.com/matreshka15/unmanned-ship-datasheets)
* [上位机端非ROS版Github地址](https://github.com/matreshka15/raspberry-pi-USV-program)
* [上位机端ROS版Github地址](https://github.com/matreshka15/ROS-based-unmanned-vehicle-project)

## 注
  * 无论上位机使用的是否为ROS版，下位机程序通用
  * 姿态算法与传感器均只与下位机(stm32)挂钩，而与上位机无关。上位机只接收下位机发送的打包好的数据。
