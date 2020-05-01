# Awesome Load Balancing Papers

- Introduction
  - List of awesome papers from various research fields in load balancing in MANET.
  - `*` after the title of paper indicates that the full paper has been carefully read by [me](https://github.com/seriouszyx).
  - A link of open source code is given if available on [Papers With Code](https://paperswithcode.com/) or [Github](https://github.com/).
  - Some papers will given links to reading notes.
  - Any [contributions](https://github.com/seriouszyx/[Load-Balance-Papers](https://github.com/seriouszyx/Load-Balance-Papers)/blob/master/.github/contribution_template.md) including PR are welcomed.

---

### Review（综述）

#### 2013

- **Investigation of Adaptive Multipath Routing For Load Balancing In MANET** [[paper](https://www.semanticscholar.org/paper/Investigation-of-Adaptive-Multipath-Routing-For-In-Sharma-Chugh/b889f4be747419ace7774d5219e7f6a463037ea1)]*

### Multi-path Routing（多径路由）

#### 2000

- **On the Impact of Alternate Path Routing for Load Balancing in Mobile Ad Hoc Networks**   (**MobiHoc2000**) [[paper](https://ieeexplore.ieee.org/document/869207)] *
  - The APR originated from the  traditional circuit witched telephone networks can reduce the end-to-end delay of  Ad Hoc networks, but routing coupling seriously affects its performance, and single channel networks is more severely affected than multiple channel networks.
  - 起源于电话交换网络的 APR 策略可以降低 Ad Hoc 网络的时延，不过路由耦合严重影响了其性能表现，单信道网络比多信道网络受的影响更严重。

#### 2009

- **Research on Multi-Path Routing Based on Load-Balance Algorithm for Ad Hoc Networks**   (**WiCOM2009**) [[paper](https://ieeexplore.ieee.org/document/5305855)] *
  - Propose a new kind of routing algorithm based on queuing theory, which calculates the usage condition of every link and the function index using the traffic matrix, and set the threshold value to limit the excessive usage of links, reduced the possibility of congestion.
  - 提出基于排队论的新型路由算法，利用流量矩阵计算出每个链路的使用情况和功能指标，设置阈值限制链接过度使用，减少拥塞的可能。

#### 2014

- **Fibonacci sequence based multipath load balancing approach for mobile ad hoc networks ** [[paper](https://www.sciencedirect.com/science/article/abs/pii/S1570870514000031)]
  - Propose Fibonacci Multipath Load Balancing protocol (FMLB), which orders the selected paths according to hops count, and the shortest path is used more frequently than the other ones.
  - 提出斐波那契多径负载均衡协议（FMLB），协议根据跳数对所选路径排序，最短路径的使用频率高于其他路径。

#### 2015

- **Energy-Aware Multipath Routing Scheme Based on Particle Swarm Optimization in Mobile Ad Hoc Networks ** [[paper](https://www.hindawi.com/journals/tswj/2015/284276/)] 
  - Propose an energy-aware multipath routing scheme based on particle swarm optimization (EMPSO) that uses continuous time recurrent neural network (CTRNN) to find the optimal loop-free paths.
  - 提出一种基于粒子群优化（EMPSO）的能量感知多径路由方案，使用连续时间递归神经网络（CTRNN）找到最佳的无环路径。

- **Load balancing maximal minimal nodal residual energy ad hoc on-demand multipath distance vector routing protocol (LBMMRE-AOMDV)** [[paper](https://link.springer.com/article/10.1007/s11276-015-1029-6)]
  - Introduce a load balancing multipath routing protocol based on maximal minimal nodal residual energy (MMRE) in the ad hoc on-demand multipath distance vector (AOMDV) protocol, which evaluates the generated paths bases on the maximal nodal residual energy and the actual number of packets that could be transmitted over that path without depleting the nodes’ energy.
  - 介绍了一种在自适应多径距离矢量（AOMDV）协议中基于最大最小节点剩余能量（MMRE）的负载均衡多径路由协议——LBMMRE-AOMDV，它能根据`最大节点剩余能量`和`在不消耗节点能量的情况下该路径上传输的实际数据包数量`来评估生成的路径。

#### 2016

- **A Scheme of Multi-path Adaptive Load Balancing in MANETs ** (**ICMMCT2016**) [[paper](https://www.researchgate.net/publication/315563092_A_Scheme_of_Multi-path_Adaptive_Load_Balancing_in_MANETs)]
  - Propose a scheme to achieve load balancing when the topology changes rapidly, according to the weights of the path quality to the weights of the quality to dynamically allocated to the multi-path data flow.
  - 提出了一种在拓扑结构发生快速变化时，根据路径质量的权重动态分配多径数据流的负载均衡方案——AOMDV-lb。

- **Enhanced Load Balancing and Delay Constraint AOMDV Routing in MANET ** (**CDAN2016**) [[paper](https://ieeexplore.ieee.org/document/7570871)]
  - Introduce rate base congestion management mechanism management the incoming and outgoing packets balance in dynamic network in the AOMDV protocol.
  - 介绍了在 AOMDV 协议中基于速率的拥塞管理机制，管理动态网络中的收发包平衡。

#### 2017

- **An efficient protocol for load-balanced multipath routing in mobile ad hoc networks** [[paper](https://www.sciencedirect.com/science/article/abs/pii/S1570870517300987)]*
  - Propose a routing protocol called the Least Common Multiple bases Routing (LCMR), which estimates the time to route a packet along each of these paths, and distribute along these multiple paths in such a way that the number of data packets sent along any such path is inversely proportional to the routing time through this path. 
  - 提出了一种基于最小公共多径路由的路由协议（LCMR），它会先估计数据包沿多条路径传输的时间，使沿着这些路径发送的数据包的数量与通过这条路径的路由时间成反比。

- **Energy Efficient Multipath Routing Protocol for Mobile Ad-Hoc Network Using the Fitness Function** [[paper](https://ieeexplore.ieee.org/document/7933071)]
  - This paper optimizes the energy consumption in AOMDV routing protocol by applying the fitness function technique, the proposed protocol is called AOMDV with the fitness function (FF-AOMDV). 
  - 本文通过应用适应度函数技术优化 AOMDV 路由协议中的能耗，提议的协议称为具有适应性功能的 AOMDV（FF-AOMDV）。

#### 2018

- **An Improved Load Balancing in MANET Using on-Demand Multipath Routing Protocol** [[paper](https://www.sciencepubco.com/index.php/ijet/article/view/22955)]
  - Apply an efficient load balancing Ad-hoc On-demand Multipath Distance Vector (LBA-AOMDV) that have the ability to maintain constant load among the nodes by balancing the traffic among  the multipath routes whenever required.
  - 应用一种有效的负载均衡自组织按需多径距离向量（AOMDV），它能够在需要时通过平衡多径路由之间的流量来维持节点间的恒定负载。