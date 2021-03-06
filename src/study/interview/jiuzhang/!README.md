九章算法的练习。  

## [新鲜出炉，Amazon SDE 面经(电面+Onsite)](http://www.jiuzhang.com/qa/3896/)  
[翻转字符串](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P053_ReverseWordsInAString.java)  
  
[划分数组](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P031_PartitionArray.java)  
注意**一个bug**。  

[链表求和。要求O（n）的时间复杂度。](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P167_AddTwoNumbers.java).  
很简单的题，结果弄错了好几次。状态不太好。  

[二叉树两个节点的最近公共祖先](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P088_LowestCommonAncestor.java).  
还是要注意如何退出递归调用问题、**有状态的类可能引入bug**的问题。  

[在一个文件中，找出所有的Anagram](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/easy/P438_FindAllAnagramsInAString.java) ★★★★★  
我的[原始方法](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/easy/P438_FindAllAnagramsInAString.java#L81)超时了。  
可以用**滑动窗口**，这也是双指针法的一种。 自己开始想不出来。注意这种思路。  

[Find smallest range containing elements from k lists](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/hard/P340_LongestSubstringWithAtMostKDistinctCharacters.java) ★★★  
LeetCode类似题目是第340题，hard。也和上一题目类似，利用**滑动窗口算法**来解决。注意写的时候还是有bug。  

[实现一个类似于并查集的数据结构，可以合并一些点的集合，并且查询点所在集合的点个数等等]  
见算法导论[第21章](https://github.com/zhuxiuwei/CLRS/blob/master/Chapter21_DisjointSets.md)，用户不相交集合的数据结构。  

[Finding max and 2nd max in an array by minimum times.](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/FindMax2ndMaxInArray.java)。  
算法导论做过这个题目。感觉有点**分治思想**在里面。  

[逆序对](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P532_ReversePairs.java) ★★★  
典型**分制**算法。算法导论第二章里也有[这个题目](https://github.com/zhuxiuwei/CLRS/blob/master/src/chap02_GettingStarted/Thinks24_Inversion_NiXuDui.java)。注意**哨兵的使用**，**和一个bug**。写的不是太顺畅，merge sort写法有点忘了。  

[设计一个LRU](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/hard/P146_LRUCache.java) ★★★  
**提交错了4次**。属于本身逻辑不算复杂，但是实现起来步骤多、繁琐，容易出错的问题。有两个注意点。  

## [Amazon HackerRank OA 面经](http://www.jiuzhang.com/qa/748/)  
题目1：Find first repeating letter in a string. 比如输入“abcba”, 返回“a”。 [代码](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/FindFirstRepeatingLetterInAString.java)  

题目2：Merge 2 arrays in 1 array. 两个sorted array都有M个元素，但是a的capacity是M， b的capacity是2M，最后是把a中的元素加入到b中，保持sorted。[代码](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Merge2ArraysInto1Array.java)  
感觉解决方法不是很优雅。虽然可以做到，每个元素只移动一次。  

题目3：Stock Maximize https://www.hackerrank.com/challenges/stockmax.  
[代码](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/StockMax.java)。和LeetCode上几个Stock Max题目都不一样（包括第二题）。  

## [Amazon Sydney 群面 09/2015](http://www.jiuzhang.com/qa/1009/)  
题目2. merge K iterator. 需要实现hasNext 和 next。 ★★  
[LeetCode](https://leetcode.com/problems/merge-k-sorted-lists/#/description)上的**Hard**题目。[代码](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/hard/P023_MergeKSortedLists.java)。有两个注意点。  

题目3. 设计红绿灯。★★★★  
没做。参看：[黑马程序员_关于交通灯管理系统的设计思路](http://blog.csdn.net/jijinhui1986/article/details/17844351)  

题目4。最简单的single number。  
[LeetCode](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/easy/P136_SingleNumber.java)做过了。略过。  

## [Amazon 面经(OA+Onsite)](http://www.jiuzhang.com/qa/2623/)
[Trap Water](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/hard/P042_TrappingRainWater.java) ★★★★★  
**REFER**  
典型**对撞型双指针**问题。当年google面过，就没答上来。[我自己的思路](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/hard/P042_TrappingRainWater.java#L47)错了，而且写起来很复杂。参考的[这个方案](https://discuss.leetcode.com/topic/3016/share-my-short-solution)。  
看了答案后，[自己又实现了一遍](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/TrapWater1.java)。  

[Minimum Window Substring](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/hard/P076_MinimumWindowSubstring.java) ★  
一次AC。和上面Anagram的题目一样思路，用**滑动窗口**方法。  

[number of island I](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/medium/P200_NumberOfIslands.java) ★★  
典型DFS问题。写起来稍微麻烦。 注意一个**投机取巧的**[点子](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/medium/P200_NumberOfIslands.java#L80)，以后可以利用。  

[Binary Tree Zigzag Level Order Traversal](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/medium/P103_BinaryTreeZigzagLevelOrderTraversal.java) ★  
二叉树层次遍历的变形。不难。  

## [Amazon 经典9题 | 独家题库, 免费 Online Judge !](https://mp.weixin.qq.com/s?__biz=MzA5MzE4MjgyMw==&mid=2649456518&idx=1&sn=1357066e1910ce736804fef716511af1&chksm=887e118ebf0998986ff9455c00e7dd76a2f20ddb76719f5787da1958938cc53cd5cde0838c97&mpshare=1&scene=1&srcid=03176Lr2wNzzdXnbczqd5Rt5&key=5657e61c2ec7753dd17978d58491302bd6abe854dfb2438ad09c292e55b6717bd174d5bb9f49aab3eb7edfb7b1fbcd1383bd01894017b5da7563d754126cecdd8ffbcc02c72c99607f8f7e342bd15cc7&ascene=0&uin=MTUyMzg3NjAwMA%3D%3D&devicetype=iMac+MacBookAir7%2C1+OSX+OSX+10.12.3+build(16D32)&version=12020010&nettype=WIFI&fontScale=100&pass_ticket=0AiIToHJN8yqpuqRAsA5PaaQMJr8KtvlnZ2EqkX0zx%2BEZweRvHKyF%2ByjmycpUbVn)  
习题描述：http://www.cnblogs.com/zcy-backend/p/6734304.html  
[maximum subtree](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_MaximumSubtree.java) ★  
比较简单。二叉树递归。有人说这是分治法。  

[Longest Palindrome](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_LongestPalindrome.java) ★  
简单。Leetcode有，重做了一次。几个注意：  
* 注意一个[bug](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_LongestPalindrome.java#L40)。  
* 修复上面的bug，同时注意用到了number of island I学到的“投机取巧”思路。  
* 第一次尝试用数组替代Map。注意数组是int[],不是char[]。  

[Rectangle Overlap](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_RectangleOverlap.java) ★  
简单。  

[window sum](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_WindowSum.java) ★  
简单。  

[Course Schedule II](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/medium/P210_CourseScheduleII.java) ★★  
典型**DFS > 拓扑排序**问题。2个注意：  
* 注意，我不用Vertex类、Color枚举类这些比较heavy的方式了，直接用Integer表示Vertex, Set<Integer>表示邻居集合。然后，基于本题业务需要，必须用grey、black两个颜色区分，这里用了个Set（visiting，visited）代表两个颜色。  
* 注意2个bug。其中第一个图初始化的错误比较严重，会导致丢失结果，其实上面【207 Course Schedule】我也犯过类似错误。  

[High Five](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_HighFive.java) ★  
比较简单。  

[K Closest Points](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_KClosestPoints.java) ★  
比较简单。有一个**for循环内部i++的bug。这种情况不是第一次遇到了，要注意**。  

[Copy List With Random Pointer](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/medium/P138_CopyListWithRandomPointer.java) ★★★  
用了**DFS**思路，不知道有没有必要。而且有一个**严重bug**。写的时候没有完全考虑清楚造成的。 

[Minimum Spanning Tree](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_MinimumSpanningTree.java) ★★★★  
《算法导论》的第23章“最小生成树”先看了。用两个算法：Kruskal和Prim。  
**[Kruskal](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_MinimumSpanningTree.java#L31)**：  
* 记录已经访问过的vertex，必须用[**并查集**](https://github.com/zhuxiuwei/CLRS/blob/master/src/chap21_DisjointSets/DisjointSetForest.java)，不能用普通的Set。 否则结果根本不对。  

**[Prim](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_MinimumSpanningTree.java#L75)**：  
* 算法本身思路虽然简单，但是实现起来**非常繁琐**。需要维护各种引用关系、集合。需要并查集的Kruskal算法相比反倒更简洁。出乎我的意料。  
* 注意[**PriorityQueue的一个限制**](https://stackoverflow.com/questions/1871253/updating-java-priorityqueue-when-its-elements-change-priority)。一旦pq建好后，修改成员里面的属性，是不会re-sort的。所以代码里必须加上很SB的[resortPriorityQueue](https://github.com/zhuxiuwei/algo/blob/master/src/study/interview/jiuzhang/Ama9Ti_MinimumSpanningTree.java#L175)函数。  
* Vertex节点的**π属性是必须**的，否则拼接List<Connection>结果集，寻找Connection的“from”会非常麻烦。π就是干这个的。  

## [Amazon 模拟面试 | 真实面试难度, 一站式在线评测](http://mp.weixin.qq.com/s?__biz=MzA5MzE4MjgyMw==&mid=2649457365&idx=1&sn=575e93d2b05830fa830f87c6f064dbd7&chksm=887eecddbf0965cbb04810f4e498b69133c22df154000a9d6b1e9a8056bfd576aeefd1bbe512&mpshare=1&scene=23&srcid=0614sGjIobjr4nIxB9w8IJBb#rd)  
[Phone Interview 1 - 53. Reverse Words in a String](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P053_AmaMoni_ReverseWordsInAString.java) ★  
做过。简单。

[Phone Interview 1 - 31. Partition Array](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P031_AmaMoni_PartitionArray.java) ★★★  
做过。但是这次没有[上次](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P031_PartitionArray.java)顺利。2个主意：  
* 注意nums[j]、nums[i]与k比较大小的时候，包不包含等于。影响后面逻辑。  
* 注意return结果，需要nums[j]和k大小不同时分情况讨论。  

[Phone Interview 2 - 167. Add Two Numbers]  
做过。简单。不做了。  

[Phone Interview 2 - 88. lowest common ancestor](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P088_AmaMoni_LowestCommonAncestor.java) ★★  
[做过](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P088_LowestCommonAncestor.java)。查找ancestors的递归，写的时候还是有bug。  

[On Site 1 - 655. Big Integer Addition](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P655_BigIntegerAddition.java) ★★  
总体顺利。1个[注意](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P655_BigIntegerAddition.java#L56)。  

[On Site 1 - 221. Add Two Numbers II](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P221_AddTwoNumbersII.java) ★  
总体顺利。和上题类似。

[On Site 2 - 158. Two Strings Are Anagrams](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P158_AmaMoni_TwoStringsAreAnagrams.java) ★★  
两个注意。总体不难。  
* 用map当hash时，要老老实实的加加减减。不要投机取巧置0或1，当有重复字符会有bug。  
* 开始用了[异或和加和](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P158_AmaMoni_TwoStringsAreAnagrams.java#L63)。**结果不对**。"az", "by"这种case会错误返回true。  

[On Site 2 - 386. Longest Substring with At Most K Distinct Characters](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P386_LongestSubstringWithAtMostKDistinctCharacters.java) ★★  
滑动窗口问题。 总体顺利。一个[bug](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P386_LongestSubstringWithAtMostKDistinctCharacters.java#L39)。  

[On Site 2 - 171. Anagrams](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P171_Anagrams.java) ★  
和<158. Two Strings Are Anagrams>类似，调用了它的方法。总体顺利。  

[On Site 3 - 479. Second Max of Array](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P479_SecondMaxOfArray.java) ★  
一次AC。简单。  

[On Site 3 - 589. Connecting Graph](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P589_ConnectingGraph.java) ★  
考察并查集(disjoint set)。顺利，一次AC。  

[On Site 4 - 532. Reverse Pairs] ★★  
[做过](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P532_ReversePairs.java)  

[On Site 4 - 134. LRU Cache](https://github.com/zhuxiuwei/algo/blob/master/src/lintcode/round1/P134_LRUCache.java) ★★★  
[做过](https://github.com/zhuxiuwei/algo/blob/master/src/LeetCode/round1/hard/P146_LRUCache.java)。不做了。  


