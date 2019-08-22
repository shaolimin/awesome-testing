##大家在做后台测试时，有哪些测试手段和测试相关知识，欢迎共建。

概念类：
接口功能测试：接口兼容性测试，接口时序测试，防重入测试，幂等性测试，API规范测试（如：Restful API），协议测试
压力测试：单机单应用压测，单链路压测，全链路压测，容量测试(评估服务的最大容量值)，
         摸高压测（在达到停止条件之后，继续增加压力，检验服务集群在失效状态下的表现），
         峰值稳定性测试，秒杀场景测试，流量蓄洪
安全测试:安全扫描（如：XSS,DDOS攻击），安全渗透测试，STRIDE威胁建模，安全sql注入测试
异常测试：Fuzzy测试，接口参数异常测试，内存泄漏测试，多进程/多线程测试，网络异常/系统异常测试
容灾测试：机房级/单机级/进程级/接口级异常演练
测试建模：MBT，ACC建模，活动图，状态机，组合测试，正交实验法
数据库/缓存测试：缓存穿透测试，事务一致性测试
精准测试：代码覆盖率分析，链路分析，
测试数据：外网引流
测试策略：数据驱动测试，混沌工程，探索性测试(exploratory testing)，A/B测试，新旧版本的对比测试
发布测试：灰度方案测试，发布方案测试，配置测试
网络拓扑测试：路由测试，负载均衡测试
分布式系统测试：
其他质量手段：代码静态扫描


工具类：
抓包/发包工具：postman, SoapUI, fiddler,wireshark
性能测试：jmeter, loadrunner, apache ab, locust, gatling压测工具
代码静态扫描：Coverity，cppcheck
代码覆盖率工具：gcover(c++),
异常模拟工具：tc网络丢包和试验模拟工具, iptables, Pumba docker异常测试, Blockade异常测试，Charybdefs文件系统异常测试，
异常注入：jvm-sandbox, aspectJ, aspectC
分布式测试：Jepsen分布式异常测试框架
自动化：python+requests, 
网络拓扑模拟：eve-ng/gns3网络拓扑模拟
安全测试工具：nmap、scapy、sqlmap、peach、burpsuite、metasploit
linux性能监控工具：CPU，内存，文件系统和磁盘I/O，网络性能(工具比较多，需要另外列出)