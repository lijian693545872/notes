# Java后台-基础知识点整理  
## [Java基础](./docs/java/README.md)： 
* 函数重载、重写
* 定义一个空参数的构造方法的作用
* 集合容器以及底层实现原理  
* String类 
* 初始化顺序的执行顺序
* 接口和类的理解  
* 反射机制和内省机制  
* java的序列化  
* 伪共享问题
* Java 中的异常处理
## [JVM相关知识点](./docs/jvm/README.md)
* java内存模型：工作内存和主内存
* java对象存储模型
* java内存结构及各个区域的作用
* 什么时候触发哪种类别的GC
* GC的算法
    * 新生代、老年代、永久代
* 类加载机制
    * 各个阶段（7个阶段）的工作流程
    * 双亲委派模式  
    * 类加载器
* JVM GC算法和垃圾收集器
## [多线程、锁](./docs/lock/README.md)
* 线程的交互
* 线程池
    * 使用好处
    * 实现原理（线程复用、管理线程）
    * 拒绝策略
    * 空闲线程超时结束
    * 线程池参数
* ScheduledThreadPoolExecutor实现原理
* 竞态条件
* 检测线程是否拥有锁
* 锁分类
    * 悲观锁/乐观锁
    * 公平锁/非公平锁
    * 独享锁/共享锁
    * 自旋锁/自适应自旋锁
    * 偏向锁/轻量级锁/重量级锁
* volatile关键字
* synchronized关键字和Lock的使用区别
* synchronized锁升级
* synchronized锁的底层原理
* AQS的实现原理
* 独占锁（ReentrantLock）的实现原理
* Condition的实现原理
* 读写锁（ReentrantReadWriteLock）的实现原理
* linkedBlockingQueue实现原理
* ConcurrentHashMap实现原理
* CountDownLatch闭锁(基于共享锁AQS)
* Semaphore（基于共享锁AQS）
* CyclicBarrier(lock实现)
## [ssm框架](./docs/framework/README.md)
* spring框架的理解
    * IOC和DI的原理和源码分析
    * AOP的实现原理
    * 事务的实现、传播行为
    * spring管理的bean的模式，默认原型
    * spring如何管理bean、bean的生命周期
* springMvc的理解
    * 接口地址和方法的映射过程
    * @ResponseBody的处理
    * @RequestMapping的处理
* Mybatis的理解
    * sql语句和方法的映射原理
    * \#｛｝ 和 \$｛｝的区别
* 拦截器、过滤器  
## [mysql（InnoDB）](./docs/mysql/README.md)
* 数据库ACID
* 事务的隔离级别
* 事务的传播行为
* 数据库锁
* 事务的实现原理
* 存储的物理结构和逻辑结构
* 数据类型及其区别
* 索引分类
* 索引实现原理（B+树）
* 自适应哈希
* 数据库优化
* MyISAM和InnoDB对比
* MVCC机制
* 快照读和当前读
## [zookeeper相关知识点](./docs/zookeeper/README.md)
* 概述
* 监听机制
* 节点读写的原子性
* 读写操作过程
* 选举过程
* zookeeper实现分布式锁
* 分布式事务解决方案
## [Kafka](./docs/kafka/README.md)
* Kafka概述、功能、场景
    * 概述
    * 功能
    * 场景
* broker及其作用
* 控制器Controller
* ISR
* 发送消息流程
## [计算机网络](./docs/ComputerNet/README.md)
* 冯诺依曼体系结构
* OSI 7层模型
* TCP 5层模型
* tcp三次握手
* tcp四次挥手
* 为什么tcp要三次握手而不是两次
* 为什么tcp要四次挥手
* 流量控制和拥塞控制
* 拥塞控制算法
* 滑动窗口协议
* http协议
* http 1.0 / 1.1 / 2.0的区别
* HTTPS
* UDP协议
## [linux常用命令](./docs/Linux/README.md)
* ps -ef|grep :查进程
* df -h /:查看磁盘使用情况
* free：查看内存使用情况
* find ./ -name test*：查看当前目录以test开头的文件或者目录
* netstat -tunlp|grep ：查看端口占用情况
* vim:V可视化模式，gg光标到首行，G到尾行
## [设计模式](./docs/design_pattern/README.md)
* 创建型模式
    * 工厂方法模式
    * 抽象工厂模式
    * 单例模式
    * 建造者模式
    * 原型模式
* 结构型模式
    * 适配器模式
    * 装饰器模式
    * 代理模式
    * 外观模式
    * 桥接模式
    * 组合模式
    * 享元模式
* 行为型模式
    * 策略模式
    * 模板方法模式
    * 观察者模式
    * 迭代器模式
    * 责任链模式
    * 命令模式
    * 备忘录模式
    * 状态模式
    * 访问者模式
    * 中介者模式
    * 解释器模式