# DataStructure-Algorithm-TS
JavaScript DataStructure and Algorithm with TypeScript
Questions on LeetCode

在线阅读地址： [数据结构和算法](https://reaperlee.cn/ds-al/)
## 数据结构
- [二叉树](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/ds/BinaryTree.md)
    - 二叉树的实现
    - 对称二叉树 ｜ LeetCode[101]
    - 二叉树镜像
    - 检测二叉平衡树
    - 二叉树的层次遍历
    - 根据先序遍历和中序遍历结果重建二叉树
    - 根据中序遍历和后序遍历结果重建二叉树
    - 路径总和
    - 二叉树展开为链表 | LeetCode [114]

- [链表](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/ds/LinkList.md)
    - 链表的实现
    - 链表的查询，插入，删除
    - 链表的正向遍历与反向遍历
    - 反转链表 | LeetCode [206]
    - 合并链表 | LeetCode [21]
    - 删除链表的倒数第N个节点 | LeetCode [19]
    - 链表节点交换 | LeetCode [24]
    - 分隔链表 | LeetCode [86]
    - 反转链表 II | LeetCode [206]
    - 重排链表 | LeetCode [143]

- [栈](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/ds/Stack.md)
    - 栈的实现
    - 栈的基础操作
    - 栈的入序和出序序列匹配检测 ｜ LeetCode [946]

- [队列](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/ds/Queue.md)
    - 队列的实现
    - 队列的基础操作
    - 循环队列的实现和基础操作 | LeetCode [622]
    - 循环双端队列 | LeetCode [641]

- [堆](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/ds/Heap.md)
    - 堆的实现
    - 堆的基础操作
- [数组](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/ds/Array.md)
    - 和为Sum的两个数字
    - 和为Sum的连续整数序列
    - 两数之和 | LeetCode [1]
    - 三数之和 | LeetCode [15]
    - 四数之和 | LeetCode [18]
    - 顺时针打印矩阵
    - 对角线遍历矩阵 | LeetCode [498]
    - 数组中出现次数超过数组一半的数字
    - 连续子数组的最大和
    - 反转字符串 | LeetCode [344]
- [字符串](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/ds/String.md)
    - 最长公共前缀 | LeetCode [14]
    - 计数二进制子串 | LeetCode [696]
    - 二进制求和 | LeetCode [67]

## 算法

#### 时间复杂度

> 一个算法的时间复杂度反映了程序运行从开始到结束所需要的时间。把算法中基本操作重复执行的此处作为算法的时间复杂度。

- `O(1)`: 常数复杂度
- `O(log n)`: 对数复杂度
- `O(n)`: 线性时间复杂度
- `O(n^2)`: 平方复杂度
- `O(n^3)`: 立方复杂度
- `O(2^n)`: 指数复杂度
- `O(!n)`: 阶乘复杂度

#### 空间复杂度

> 空间复杂度是指运行完一个程序所需内存的大小。利用程序的空间复杂度，可以对程序的运行所需内存有预先估计。

一个程序执行时除了需要存储空间和存储本身所使用的指令、常数、变量和输入数据外，还需要一些对数据进行操作的工作单元和存储一些为实现计算所需信息的辅助空间。


### 算法目录
- [排序](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/al/Sort.md)
    - 插入排序  
    - 冒泡排序
    - 选择排序
    - 快速排序
    - 归并排序
    - 堆排序

- [递归](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/al/Recursion.md)
    - 斐波那契数列 | LeetCode [509]
    - 爬楼梯 | LeetCode [70]
    - Pow 「求x的n次幂」 | LeetCode [50]

- [动态规划](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/al/DynamicProgramming.md)
    - 斐波那契数列 ｜ LeetCode [509]
    - 泰波那契数列 | LeetCode [1137]
    - 杨辉三角 | LeetCode [118]
    - 打家劫舍 | LeetCode [198]
    - 打家劫舍 II | LeetCode [213]
- [贪心算法](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/GreedyAlgorithm/GreedAlgorithm.md)
    - 买卖股票的最佳时机 | LeetCode [121]
    - 买卖股票的最佳时机II | LeetCode [122]
    - 买卖股票的最佳时机（含手续费） | LeetCode [714]
    - 分发饼干 | LeetCode [455]
- [二分查找](https://github.com/Reaper622/DataStructure-Algorithm-TS/tree/master/docs/Search/Search.md)
    - 二分查找的实现 | LeetCode [704]
    - 二分求解`x`的平方根 | LeetCode [69]
    - 搜索旋转排序数组 | LeetCode [33]
    - 寻找峰值 | LeetCode [162]
    - 寻找旋转排序数组中的最小值 | LeetCode [153]
    - 在排序数组中查找元素的第一个和最后一个位置 | LeetCode [34]
    - 找到K个最接近的元素 | LeetCode [658]
    - 寻找比目标字母大的最小字母 | LeetCode [744]