# 2.实践部分-小车拼装

### 一、元件清单
&emsp;&emsp;底座及其连接器x4、锂电池x1、电池充电器x1、主轮x2、辅助轮x1、电 机x2、亚历克板x1、超声波传感器x2、超声波传感器支架x2（配套螺丝）、 NVIDIA开发板x1、Arduino Sensor Shield v5.0 x1、VNH5019 x1、Arduino Mega 2560及其USB数据线 x1、六边形螺丝刀x2、电路开关 x1、电路一套、螺丝一袋、串口线20根。各小组要明确分工，有序组装，螺丝稀缺，不能出现人多手杂弄丢元件的情况。
### 二、安装步骤
1.安装底座，取**8颗短螺丝及颗长螺丝**、4根底座及连接器。先将一个连接器与一根底座按图1方式连接，注意！**底座边角锋利，注意不要割伤或者碰到别人**：
<center><img src="/assets/d1.png"/></center>

再将第二根底座与该连接器连接，如下图所示：
<center><img src="/assets/d2.png"/></center>

其余底座按同样方式连接在一起，为方便后续步骤，**建议所有底座开口都向外**，最终效果如下图:
<center><img src="/assets/d3.png"/></center>

2.将底座与电机连接，先将电机与其连接套件连接，如图 4，再将电机与底座连接，如图 5，将另一个电机用相同方法连接。**注意！两个主轮必须在同一个轴上**。

<center><img src="/assets/d4.png"/></center>
<center><img src="/assets/d5.png"/></center>

3.将辅助轮与底座连接，如图6，将主轮通过连接套件与电机连接如图7，至此小车整体框架安装完成。
<center><img src="/assets/d6.png"/></center>

<center><img src="/assets/d7.png"/></center>


4.固定亚历克板，取 4 颗长螺丝及螺帽（如果只有两个螺帽则固定对角线）。<br>
5.用双面胶带将 Arduino Mega2560（已和 VNH5019 及 Arduino Sensor Shield 连接好）固定在亚历克板上，将锂电池用尼龙扎带固定在亚历克板上， 将 miniand 用双面胶带固定在亚历克板上，将转压元件和电路开关固定在合适 的位置。

<center><img src="/assets/d8.png"/></center>

6.连线，先将，两根主线与电路开关相连，如图 9。接着将黄色插头插入锂电池的接口中，如图10-1，**注意！红色线对应红色线，黑色线对应黑色线**。 然后将 VNH5019 电源线左右两边的杜邦线分别插入左右两个电机的红色和黑色的引脚中，如图10-2。最后将剩下的红色粗线和黑色粗线接入到转压元件的 另一端，此处部分不分正负极，如图10-3。**对于太长的线可以用短的尼龙扎带加以整理**。
<center><img src="/assets/d9.png"/></center>
<center><img src="/assets/d10.png"/></center>

7.安装超声波传感器，传感器共两个小车前面一个，右边一个（辅助轮一方为后），首先将传感器固定在其支架上，再将支架通过螺丝固定在底座上，如下图
<center><img src="/assets/d11.png"/></center>

8.连接超声波传感器，首先将gnd 和vcd 两个针脚与 Arduino Sensor Shield 上的g和v两个针脚连接，**注意 gnd 和 g，vcd 和 v 对应，这两个针脚负责供电，不要连反**，接着将 trig 和 echo 两个引脚分别连到 Arduino 对应的引脚上，**注意！前方传感器的 Trig 对应 A2号引脚，Echo 对应 A3 号引脚，右侧传感器的Trig 对应 A0号引脚，Echo 对应 A1 号引脚。**最后将 NVIDIA 和 Arduino 用 USB 线连接。安装完成，效果如下图

<center><img src="/assets/d12.png"/></center>

**其他注意事项：确保 NVIDIA 和 Arduino 已经通过 USB 线连接后再通电； 连接电路时千万不能使电路短路；小车启动后的无线网络名为：Blockly_编号，如5号车为Blockly_5，所有小 车IP 均为：10.42.0.1，TCP端口均为 8080；初次安装完成后可能出现电机反转的情况，交换其电源线的顺序即可，请自行测试；安装完成后先不要通电，等待我们检查后方可接通电源**
<p style="text-align: right;">联系方式：周庆国,<img src="/assets/biaozhi.png" style="width: 15px;height: 15px;">zhouqg@lzu.edu.cn<p>

