# This is my first Blog.

## DAY 2021-1-26

### 并发测试总结

* chorme录制jmeter测试脚本插件：blazemeter （可在chrome商店搜索到）
* springboot项目并发配置：
      maxConnections： 最大连接数   指在同一时间，tomcat能够接受的最大连接数
      maxThreads：     最大线程数   最大线程数决定了Web服务容器可以同时处理多少个请求  线程数的经验值为：1核2g内存为200，线程数经验值200；4核8g内存，线程数经验值800
      accept-count：   最大等待数   当所有的请求处理线程（既maxThreads达到最大值）都在使用时，所能接收的连接请求的队列的最大长度
  [参考文档](https://blog.csdn.net/crazymakercircle/article/details/102768912?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.control)
