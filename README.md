# AndroidPerformanceTest_Java

简述
---
这是一个java版本的Android性能数据产出的sdk

实现功能
---
1. pss内存占用率
2. 应用网络消耗流量
3. 应用缓存占用量，应用数据占用量，应用代码占用量。
4. cpu占用率
5. vss内存占用率
6. rss内存占用率
7. 结合AnyProxy能够拿到网络数据包


注意
---
其中网络流程，应用缓存需要辅助apk来获取，目前辅助apk代码还没有开源

目前代码中Android相关对应的工具并未进行环境变量的读取，由于Java读取之前一直存在bug，所以之后会增加一个配置文件来读取。现在hard code中。
