### 源码：
docs文件夹中是源码，就一个 html 文件。

### 演示地址：
https://liu-shichao.github.io/solfeggio/


### 介绍
唱名练习工具，根据【参考】里的课程制作的练习工具，练习音乐唱名的工具


### 使用方法：
1. 选择当前要练习的是第几天
2. 跟随生成的唱名进行唱读练习，do re mi fa so la xi

### 原理解释：
1.根据下边的这个规则，生成随机的 1234567 ，进行唱名练习，总共 15 天
```
// 第一天
145
236
467
126
357
// 2 - 3 天
2567
1457
2367
1356
1245
// 4 - 6 天
12456
23567
13567
23467
34567
// 7 - 10 天
234567
134567
123467
123567
124567
// 11 - 15 天
七个音一起按，想按多长按多长
```
### 参考：
1.【零基础学音乐·自学乐理】2-“唱名”与记住“唱名”的方法： https://www.bilibili.com/video/BV1954y1C7qM/?spm_id_from=333.788&vd_source=55a350b8650fa259fcd33c6529c36cf5