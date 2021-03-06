### 2.3 工业过程控制

　　过程和制造工业的自动化发轫于十九世纪末期，并在二十世纪初加速发展。化工、石油、造纸、制药工业的生产过程需要精确地控制压力、温度和流量来得到好的产品质量。锅炉、反应堆、精馏塔、混合器和搅拌器是典型的工业过程。多种用来测量不同物理量的传感器被研制了出来。典型的控制机构是阀门和气泵，利用气动设备完成感知、执行和控制功能是	常用的技术。传感器和执行器必须安装在工业过程的环境中。最开始，控制器也和工业过程设备安装在一起。他们通过压力信号同传感器和驱动器通信。连接器、压力管以及信号水平（3-15psi）成为标准，从而使得不同厂商的设备可以协同工作。后来，控制器被合并移动到中央控制室，也在那里提供仪器记录信号，这样极大地简化了操作人员的工作环节与工作环境。
  
　　那时的控制器发展并不是由理论推动的，而是基于工程应用的考量。通过修葺，人们重新发现了积分和微分的效用。对泰勒仪器公司（Taylor Instrument Company）齐格勒（John Ziegler）的采访(Blickley, 1990)给出了这样的观点:
> 
**“研发部的一些人在修葺一种称为Fulscope的气动比例积分控制器，反馈给容器的线路以某种方式得到了限制，这个限制产生了波纹管中的跟随特性。他注意到这个方法对于输出有奇特而显著的作用。他们在人造纤维粉碎机上试验了这个方法，获得了完美的温度控制结果。”**

　　控制器组件也被用作气动模拟控制器来仿真工业过程。因为模拟器使用了气动信号，所以可以很方便地连接到气动控制器。反馈在传感器、执行器和控制器本身中广泛使用。关键思想是用高增益的气动放大器以限制量的形式把被动部件组合起来，从而产生优良的线性行为。这同后面2.6节讨论的反馈放大器十分相似。
  
　　控制器开始变成一种标准化的通用型设备，而不再是为像调速器这样的特殊过程而构造，并且它们还配备了刻度盘来调节PID控制器的参数。最早的通用型PID控制器是由Foxboro研发的Stabilog，它的增益可以在0.7~100之间调节。它在1931年出现，很快其他厂商就开发了相似的产品。因为同一个过程可能会用到很多控制器，因此人们需要一种为不同过程的控制器寻找合适参数值的方法。齐格勒和尼克尔斯发展了一套整定准则(1942)，仅需在这些过程中做一些简单的实验就可以确定控制参数。
  
　　传感器、仪表和控制器的出现使得一些新公司随之诞生。工业界变得高度多样化，到二十世纪三十年代中期已有超过600家控制公司，其中的领先者包括Bailey、Brown、Fisher & Porter、Foxboro、Honeywell、Kent、Leeds & Northrup、西门子（Siemens）、泰勒仪器和Yokogawa(Strothman, 1995)。Bennett (1993, p. 28)估计在1925-1935年间美国共卖出了约75000个控制器。
  
　　过程控制的工业结构与通信和电力行业是不同的。想法并没有得到广泛传播，而是作为商业机密被保护起来。过程控制领域有大量的公司。通信和电力行业可获得的集中资源正是过程工业所缺少的，就像前两者缺少理论基础一样。

（夜行译）
