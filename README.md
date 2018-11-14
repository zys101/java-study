# java-study
## 多线程并发编程

### 1 Java基础
* 1.1 JAVA程序运行堆栈分析
* 1.2 线程状态
* 1.3 线程中止
* 1.4 内存屏障和CPU缓存
* 1.5 线程通信
* 1.6 线程封闭之ThreadLocal和栈封闭
* 1.7 线程池应用及实现原理剖析

### 2 线程安全之可见性问题

+ 2.1 使用volatile解决可见性问题及阻止指令重排序
+ 2.2 线程安全之共享资源 / 不可变性 / 竟态条件 / 临界区
+ 2.3 线程安全之原子操作
+ 2.4 Atomic相关类和CAS机制
+ 2.5 JAVA锁相关术语及同步关键字synchronized详解
+ 2.6 Lock接口  和 ReentrantLock / ReadWriteLock

### 3 J.U.C并发编程包详解

+ 3.1 AQS抽象队列同步器详解
+ 3.2 FutureTask源码剖析
+ 3.3 并发容器类-ConcurrentHashMap / ConcurrentSkipListMap
+ 3.4 并发容器类2- / ConcurrentSkipListSet / ConcurrentLinkedQueue  / CopyOnWriteArrayList / LinkedBlockingQueue
+ 3.5 Fork/Join框架详解
+ 3.6 工具类拓展-信号量和栅栏和倒计数器

##  高并发网络编程

### 1 Java NIO网络编程

+ 1.1 TCP/UDP协议
+ 1.2 BIO阻塞式网络编程
+ 1.3 NIO非阻塞网络编程三大核心理念

### 2 Netty框架源码学习

+ 2.1 netty线程模型
+ 2.2 零拷贝机制
+ 2.3 责任链设计模式

### 3 网络编程项目实践

+ 3.1 推送系统功能实现
+ 3.2 系统优化 - 百万连接

## Java系统性能调优

### 1 JVM性能篇

1. 1 JVM内存模型详解
1. 2 类加载机制
1. 3 垃圾回收机制
1. 4 JVM内置命令工具

### 2 性能调优综合实战

2. 1 Tomcat网络处理线程模型
2. 2 参数调优
2. 3 JVM参数及调优
3. 4 内存爆炸、CPU100%问题分析、定位、解决

