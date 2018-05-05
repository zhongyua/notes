# 性能测试

## 性能测试的目的：发现性能瓶颈

### 性能测试的分类

#### 概念

- 性能测试是一个非常广泛的概念，包括很多方面的测试，也可称之为非功能测试。
- 自动化测试属于功能测试的范围，由于其测试方法要求测试人员拥有一定的代码能力，所以被单独分成一个测试模块。


#### 具体分类（测试范围）

- 负载测试：通过逐步加压的方法，达到既定的性能阈值的目标，阈值的设定应是小于等于某个值，如cpu使用率小于等于80%。
- 压力测试：通过逐步加压的方法，使得系统的某些资源达到饱和，甚至失效的状态，简单粗暴的解释就是什么条件能把系统压奔溃。
- 并发测试：在同一时间内，多个虚拟用户同时访问同一个模块、同一功能，通常的测试方法是设置集合点。