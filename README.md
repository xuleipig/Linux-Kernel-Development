# Linux-Kernel-Development
## 第一章 Linux内核简介
1 操作系统是整个系统中负责完成最基本功能和系统管理的那些部分，这些部分应该包括内核、设备驱动程序、启动引导程序、命令行Shell或者其他种类的用户界面、基本的文件管理工具和系统工具。  
2 内核由负责响应中断的中断服务程序，负责管理多个进程从而分享处理器时间的调度程序，负责管理进程地址空间的内存管理程序和网络、进程间通信等系统服务程序共同组成。  
3 单内核：内核从整体上作为一个单独的大过程来实现，同时也运行再一个单独的地址空间上。内核可以直接调用函数，linux是单内核。    
4 微内核：微内核的功能被划分为多个独立的过程，每个过程叫做一个服务器。  
## 第二章 从内核出发
### 内核开发的特点
1 无libc库或无标准头文件  
2 GUN C  
3 没有内存保护机制  
4 不要轻易的在开发中使用浮点数  
5 容积小而固定的栈  
6 同步和并发  
7 可移植性  

