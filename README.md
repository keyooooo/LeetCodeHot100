# 个人自用题单

---

## 🏁 第一阶段：熟悉底层容器


### 1. 哈希表（空间换时间，查重与映射）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [1. 两数之和](https://leetcode-cn.com/problems/two-sum) | [题解](https://leetcode-cn.com/problems/two-sum/solution/1-liang-shu-zhi-he-by-tonngw-j0do/) | 哈希表 $O(1)$ 查找的威力 |
| [128. 最长连续序列](https://leetcode-cn.com/problems/longest-consecutive-sequence) | [题解](https://leetcode-cn.com/problems/longest-consecutive-sequence/solution/by-tonngw-k87f/) | 体会如何利用哈希集合把 $O(n^2)$ 降到 $O(n)$ |
| [49. 字母异位词分组](https://leetcode-cn.com/problems/group-anagrams) | [题解](https://leetcode-cn.com/problems/group-anagrams/solution/by-tonngw-bqjz/) | 将排序后的字符串作为哈希表的 Key |

### 2. 数组基本操作与位运算
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [169. 多数元素](https://leetcode-cn.com/problems/majority-element) | [题解](https://leetcode-cn.com/problems/majority-element/solution/by-tonngw-ulqh/) | 摩尔投票法，或者哈希计数 |
| [448. 找到所有数组中消失的数字](https://leetcode-cn.com/problems/find-all-numbers-disappeared-in-an-array) | [题解](https://leetcode-cn.com/problems/find-all-numbers-disappeared-in-an-array/solution/by-tonngw-d3o1/) | 原地哈希（用正负号当标记） |
| [136. 只出现一次的数字](https://leetcode-cn.com/problems/single-number) | [题解](https://leetcode-cn.com/problems/single-number/solution/by-tonngw-26ks/) | 异或运算 `^` 的神工鬼斧（自反性） |
| [461. 汉明距离](https://leetcode-cn.com/problems/hamming-distance) | [题解](https://leetcode-cn.com/problems/hamming-distance/solution/by-tonngw-me59/) | 异或后统计二进制中 1 的个数 |
| [338. 比特位计数](https://leetcode-cn.com/problems/counting-bits) | [题解](https://leetcode-cn.com/problems/counting-bits/solution/by-tonngw-klsi/) | 位运算与递推结合 |
| [48. 旋转图像](https://leetcode-cn.com/problems/rotate-image) | [题解](https://leetcode-cn.com/problems/rotate-image/solution/by-tonngw-yncd/) | 矩阵的对角线翻转与左右翻转 |
| [238. 除自身以外数组的乘积](https://leetcode-cn.com/problems/product-of-array-except-self) | [题解](https://leetcode-cn.com/problems/product-of-array-except-self/solution/by-tonngw-l4xc/) | 构造前缀乘积阵列与后缀乘积阵列 |

---

## 📈 第二阶段：线性结构的物理移动


### 3. 普通双指针（双向对撞与快慢指针）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [283. 移动零](https://leetcode-cn.com/problems/move-zeroes) | [题解](https://leetcode-cn.com/problems/move-zeroes/solution/283-yi-dong-ling-by-tonngw-x0zd/) | 快慢指针最基础的用法 |
| [11. 盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water) | [题解](https://leetcode-cn.com/problems/container-with-most-water/solution/shuang-zhi-zhen-miao-jie-11-sheng-zui-du-3235/) | 对撞指针，理解为什么舍弃短板是安全的 |
| [15. 三数之和](https://leetcode-cn.com/problems/3sum) | [题解](https://leetcode-cn.com/problems/3sum/solution/15-san-shu-zhi-he-by-tonngw-cs4b/) | 排序 + 定位一个数 + 双指针对撞（注意去重） |
| [75. 颜色分类](https://leetcode-cn.com/problems/sort-colors) | [题解](https://leetcode-cn.com/problems/sort-colors/solution/75-yan-se-fen-lei-by-tonngw-v7fl/) | 三指针，荷兰国旗问题（左、中、右区域划分） |
| [5. 最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring) | [题解](https://leetcode-cn.com/problems/longest-palindromic-substring/solution/5-zui-chang-hui-wen-zi-chuan-by-tonngw-1i6u/) | 双指针中心扩散法 |
| [647. 回文子串](https://leetcode-cn.com/problems/palindromic-substrings) | [题解](https://leetcode-cn.com/problems/palindromic-substrings/solution/647-hui-wen-zi-chuan-by-tonngw-4ftv/) | 同样用中心扩散法计数，比动态规划更高效 |

### 4. 经典链表（指针大乱斗，务必画图）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [206. 反转链表](https://leetcode-cn.com/problems/reverse-linked-list) | [题解](https://leetcode-cn.com/problems/reverse-linked-list/solution/206-fan-zhuan-防链表-by-tonngw-brl7/) | 链表操作的基本功中的基本功 |
| [21. 合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists) | [题解](https://leetcode-cn.com/problems/merge-two-sorted-lists/solution/by-tonngw-2axu/) | 迭代双指针，虚拟头节点（Dummy Head）的运用 |
| [141. 环形链表](https://leetcode-cn.com/problems/linked-list-cycle) | [题解](https://leetcode-cn.com/problems/linked-list-cycle/solution/141-huan-xing-lian-biao-by-tonngw-2gsc/) | 快慢指针（弗洛伊德判圈法） |
| [142. 环形链表 II](https://leetcode-cn.com/problems/linked-list-cycle-ii) | [题解](https://leetcode-cn.com/problems/linked-list-cycle-ii/solution/142-huan-xing-lian-biao-ii-by-tonngw-uem5/) | 快慢指针相遇后，头指针与慢指针同步走碰头 |
| [160. 相交链表](https://leetcode-cn.com/problems/intersection-of-two-linked-lists) | [题解](https://leetcode-cn.com/problems/intersection-of-two-linked-lists/solution/by-tonngw-yadv/) | “浪漫相遇法”：走到尽头换对方的路走，消除长度差 |
| [234. 回文链表](https://leetcode-cn.com/problems/palindrome-linked-list) | [题解](https://leetcode-cn.com/problems/palindrome-linked-list/solution/234-hui-wen-lian-biao-by-tonngw-6ee4/) | 快慢指针找中点 + 后半段链表反转 + 双指针对比 |
| [19. 删除链表的倒数第 N 个结点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list) | [题解](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/solution/19-shan-chu-lian-biao-de-dao-shu-di-n-ge-c2s0/) | 前后指针，保持固定距离 $N$ 同步前移 |
| [2. 两数相加](https://leetcode-cn.com/problems/add-two-numbers) | [题解](https://leetcode-cn.com/problems/add-two-numbers/solution/2-liang-shu-xiang-jia-by-tonngw-t6kn/) | 链表模拟加法，注意处理最后的进位 |
| [23. 合并K个升序链表](https://leetcode-cn.com/problems/merge-k-sorted-lists) | [题解](https://leetcode-cn.com/problems/merge-k-sorted-lists/solution/23-he-bing-kge-sheng-xu-lian-biao-by-ton-c67k/) | 分治合并，或者用小顶堆（优先队列） |
| [148. 排序链表](https://leetcode-cn.com/problems/sort-list) | [题解](https://leetcode-cn.com/problems/sort-list/solution/by-tonngw-jdfp/) | 链表的归比排序（找中点 + 合并两个有序链表） |
| [146. LRU 缓存](https://leetcode-cn.com/problems/lru-cache) | [题解](https://leetcode-cn.com/problems/lru-cache/solution/146-lru-huan-cun-by-tonngw-i7pj/) | 哈希表 + 双向链表（手写数据结构的经典面试题） |
| [287. 寻找重复数](https://leetcode-cn.com/problems/find-the-duplicate-number) | [题解](https://leetcode-cn.com/problems/find-the-duplicate-number/solution/by-tonngw-v1x5/) | 巧妙转化：把数组看成带环链表，用快慢指针解决 |

### 5. 进阶线性窗：滑动窗口与前缀和（专门对付“连续子数组/子串”）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [3. 无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters) | [题解](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/solution/by-tonngw-vu6h/) | 最标准的滑动窗口入门题 |
| [438. 找到字符串中所有字母异位词](https://leetcode-cn.com/problems/find-all-anagrams-in-a-string) | [题解](https://leetcode-cn.com/problems/find-all-anagrams-in-a-string/solution/438-zhao-dao-zi-fu-chuan-zhong-suo-you-z-q79l/) | 固定长度的滑动窗口 + 数组哈希计数 |
| [560. 和为 K 的子数组](https://leetcode-cn.com/problems/subarray-sum-equals-k) | [题解](https://leetcode-cn.com/problems/subarray-sum-equals-k/solution/by-tonngw-f2g3/) | **前缀和 + 哈希表**！有负数时滑动窗口会瘫痪，只能用它 |
| [76. 最小覆盖子串](https://leetcode-cn.com/problems/minimum-window-substring) | [题解](https://leetcode-cn.com/problems/minimum-window-substring/solution/hua-dong-chuang-kou-suan-fa-76-zui-xiao-3y39p/) | 滑动窗口终极天花板（困难题），严格维护窗口内的字符频数 |

### 6. 普通栈与队列的应用
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [20. 有效的括号](https://leetcode-cn.com/problems/valid-parentheses) | [题解](https://leetcode-cn.com/problems/valid-parentheses/solution/si-lu-qing-xi-dai-ma-jian-ji-de-xie-fa-2-e83j/) | 栈的经典应用：左括号压栈，右括号弹栈对比 |
| [155. 最小栈](https://leetcode-cn.com/problems/min-stack) | [题解](https://leetcode-cn.com/problems/min-stack/solution/by-tonngw-79zb/) | 辅助栈同步存储当前栈的最小值 |
| [394. 字符串解码](https://leetcode-cn.com/problems/decode-string) | [题解](https://leetcode-cn.com/problems/decode-string/solution/by-tonngw-vspj/) | 数字栈和字符串栈协同处理括号嵌套 |
| [347. 前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements) | [题解](https://leetcode-cn.com/problems/top-k-frequent-elements/solution/347-qian-k-ge-gao-pin-yuan-su-by-tonngw-a12g/) | 哈希表统计频次 + 小顶堆（优先队列）动态维护前K个 |

---

## 🌲 第三阶段：树与图的遍历（理解“递归”与“深度搜索”）

从“线性结构”变成“树状拓扑扩散”。核心在于攻克递归心理关。

### 7. 二叉树与二叉搜索树（全面轰炸递归思想）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [94. 二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal) | [题解](https://leetcode-cn.com/problems/binary-tree-inorder-traversal/solution/94-er-cha-shu-de-zhong-xu-bian-li-by-ton-6i82/) | 递归基本功，或者用栈迭代实现 |
| [102. 二叉树的层序遍历](https://leetcode-cn.com/problems/binary-tree-level-order-traversal) | [题解](https://leetcode-cn.com/problems/binary-tree-level-order-traversal/solution/102-er-cha-shu-de-ceng-xu-bian-li-by-ton-zt9s/) | 使用队列进行 BFS，按层隔离输出 |
| [226. 翻转二叉树](https://leetcode-cn.com/problems/invert-binary-tree) | [题解](https://leetcode-cn.com/problems/invert-binary-tree/solution/226-fan-zhuan-er-cha-shu-by-tonngw-8v8z/) | 递归交换左右子树 |
| [104. 二叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree) | [题解](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/solution/104-er-cha-shu-de-zui-da-shen-du-by-tonn-zen4/) | 树的深度 = `max(左深度, 右深度) + 1` |
| [101. 对称二叉树](https://leetcode-cn.com/problems/symmetric-tree) | [题解](https://leetcode-cn.com/problems/symmetric-tree/solution/101-dui-cheng-er-cha-shu-by-tonngw-zoj1/) | 两个指针同步判断：左的左和右的右是否相等 |
| [543. 二叉树的直径](https://leetcode-cn.com/problems/diameter-of-binary-tree) | [题解](https://leetcode-cn.com/problems/diameter-of-binary-tree/solution/543-er-cha-shu-de-zhi-jing-by-tonngw-mc3x/) | 在求深度的递归过程中，顺便更新最大路径长（左深+右深）|
| [617. 合并二叉树](https://leetcode-cn.com/problems/merge-two-binary-trees) | [题解](https://leetcode-cn.com/problems/merge-two-binary-trees/solution/617-he-bing-er-cha-shu-by-tonngw-aizw/) | 同步递归遍历两棵树，合并重叠节点 |
| [114. 二叉树展开为链表](https://leetcode-cn.com/problems/flatten-binary-tree-to-linked-list) | [题解](https://leetcode-cn.com/problems/flatten-binary-tree-to-linked-list/solution/by-tonngw-m6ek/) | 前序遍历的变形，或者寻找左子树的最右节点连接 |
| [98. 验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree) | [题解](https://leetcode-cn.com/problems/validate-binary-search-tree/solution/98-yan-zheng-er-cha-sou-suo-shu-by-tonng-nsg4/) | 利用中序遍历是严格升序的特性进行校验 |
| [538. 把二叉搜索树转换为累加树](https://leetcode-cn.com/problems/convert-bst-to-greater-tree) | [题解](https://leetcode-cn.com/problems/convert-bst-to-greater-tree/solution/538-ba-er-cha-sou-suo-shu-zhuan-huan-wei-kse8/) | 反向中序遍历（右 -> 中 -> 左），累加历史和 |
| [236. 二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree) | [题解](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/solution/236-er-cha-shu-de-zui-jin-gong-gong-zu-x-ok6d/) | 后序遍历回溯：左右子树各自发现了目标节点，则当前节点为祖先 |
| [105. 从前序与中序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | [题解](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/solution/105-cong-qian-xu-yu-zhong-xu-bian-li-xu-wgoxg/) | 前序定根，中序切分左右子树区间 |
| [437. 路径总和 III](https://leetcode-cn.com/problems/path-sum-iii) | [题解](https://leetcode-cn.com/problems/path-sum-iii/solution/by-tonngw-4xws/) | 树上的前缀和！将前缀和哈希表应用到树的 DFS 回溯中 |
| [124. 二叉树中的最大路径和](https://leetcode-cn.com/problems/binary-tree-maximum-path-sum) | [题解](https://leetcode-cn.com/problems/binary-tree-maximum-path-sum/solution/124-er-cha-shu-zhong-de-zui-da-lu-jing-h-v7ms/) | 困难题。节点最大贡献度计算，注意舍弃负资产贡献 |
| [297. 二叉树的序列化与反序列化](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree) | [题解](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree/solution/by-tonngw-rk2y/) | 将树变为字符串，再将字符串复原（DFS或BFS均可） |
| [208. 实现 Trie (前缀树)](https://leetcode-cn.com/problems/implement-trie-prefix-tree) | [题解](https://leetcode-cn.com/problems/implement-trie-prefix-tree/solution/by-tonngw-i32p/) | 字典树结构设计，每个节点包含 26 个子节点指针 |

### 8. 回溯算法（全排列与组合：穷举的艺术）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [78. 子集](https://leetcode-cn.com/problems/subsets) | [题解](https://leetcode-cn.com/problems/subsets/solution/78-zi-ji-by-tonngw-bhjq/) | 回溯算法最标准、最干净的入门模板 |
| [17. 电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number) | [题解](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number/solution/17-dian-hua-hao-ma-de-zi-mu-zu-he-by-ton-fwvm/) | 多层集合的笛卡尔积穷举 |
| [39. 组合总和](https://leetcode-cn.com/problems/combination-sum) | [题解](https://leetcode-cn.com/problems/combination-sum/solution/39-zu-he-zong-he-by-tonngw-oqyt/) | 元素可无限重复选取，回溯时控制控制起始下标 `start` 避免重复 |
| [46. 全排列](https://leetcode-cn.com/problems/permutations) | [题解](https://leetcode-cn.com/problems/permutations/solution/46-quan-pai-lie-by-tonngw-08i3/) | 使用 `used` 数组标记已被选中的元素，体会状态重置（回溯）|
| [22. 括号生成](https://leetcode-cn.com/problems/generate-parentheses) | [题解](https://leetcode-cn.com/problems/generate-parentheses/solution/22-gua-hao-sheng-cheng-hui-su-mei-ju-suo-igx9/) | 剪枝策略：左括号数量随时大于等于右括号数量才合法 |
| [79. 单词搜索](https://leetcode-cn.com/problems/word-search) | [题解](https://leetcode-cn.com/problems/word-search/solution/by-tonngw-9sc2/) | 网格中的矩阵内深度搜索（矩阵回溯） |
| [301. 删除无效的括号](https://leetcode-cn.com/problems/remove-invalid-parentheses) | [题解](https://leetcode-cn.com/problems/remove-invalid-parentheses/solution/by-tonngw-w2sl/) | 困难题。先计算最少删除数，再通过回溯法去重爆破 |

### 9. 图论与广度优先搜索（BFS）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [200. 岛屿数量](https://leetcode-cn.com/problems/number-of-islands) | [题解](https://leetcode-cn.com/problems/number-of-islands/solution/200-dao-yu-shu-liang-by-tonngw-zqm2/) | 网格染色的 DFS/BFS，遇到 1 就把四周全部淹没成 0 |
| [207. 课程表](https://leetcode-cn.com/problems/course-schedule) | [题解](https://leetcode-cn.com/problems/course-schedule/solution/by-tonngw-gi4x/) | 拓扑排序，检测有向图中是否存在环（入度数组+队列）|
| [399. 除法求值](https://leetcode-cn.com/problems/evaluate-division) | [题解](https://leetcode-cn.com/problems/evaluate-division/solution/by-tonngw-fp8u/) | 构建有向带权图，使用 DFS 进行路径权值乘积搜索 |

---

## ⚔️ 第四阶段：算法


### 10. 二分查找（折半搜索与边界控制）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | [题解](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/solution/34-zai-pai-xu-shu-zu-zhong-cha-zhao-yuan-mm3f/) | 最经典的二分查找：寻找左边界与右边界 |
| [33. 搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array) | [题解](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/solution/33-sou-suo-xuan-zhuan-pai-xu-shu-zu-by-t-nryt/) | 局部有序的二分，判断哪半边是有序的再做收缩 |
| [240. 搜索二维矩阵 II](https://leetcode-cn.com/problems/search-a-2d-matrix-ii) | [题解](https://leetcode-cn.com/problems/search-a-2d-matrix-ii/solution/by-tonngw-xjrx/) | 从矩阵右上角或左下角开始进行“Z字形查找” |
| [4. 寻找两个正序数组的中位数](https://leetcode-cn.com/problems/median-of-two-sorted-arrays) | [题解](https://leetcode-cn.com/problems/median-of-two-sorted-arrays/solution/by-tonngw-sba5/) | 困难题。通过划分数组，在两个有序数组上做二分切分 |

### 11. 单调栈与单调队列（对付“下一个更大”或“区间最值”）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [739. 每日温度](https://leetcode-cn.com/problems/daily-temperatures) | [题解](https://leetcode-cn.com/problems/daily-temperatures/solution/739-mei-ri-wen-du-by-tonngw-g24w/) | 单调栈入门：寻找右边第一个比当前数大的位置 |
| [42. 接雨水](https://leetcode-cn.com/problems/trapping-rain-water) | [题解](https://leetcode-cn.com/problems/trapping-rain-water/solution/42-jie-yu-shui-san-ci-xian-xing-sao-miao-15ks/) | 面试高频！可用双指针，也可用单调栈横向计算水槽面积 |
| [84. 柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram) | [题解](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/solution/84-zhu-zhuang-tu-zhong-zui-da-de-ju-xing-gjcg/) | 单调栈进阶：寻找左右两侧第一个比当前柱子矮的边界 |
| [85. 最大矩形](https://leetcode-cn.com/problems/maximal-rectangle) | [题解](https://leetcode-cn.com/problems/maximal-rectangle/solution/by-tonngw-8s1f/) | 将二维矩阵按行拆解，转化为第 84 题的柱状图最大矩形 |
| [239. 滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum) | [题解](https://leetcode-cn.com/problems/sliding-window-maximum/solution/239-hua-dong-chuang-kou-zui-da-zhi-by-to-aac7/) | **单调队列**。维护队列单调递减，窗口移动时踢出过期最大值 |

### 12. 贪心算法（局部最优解）
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [55. 跳跃游戏](https://leetcode-cn.com/problems/jump-game) | [题解](https://leetcode-cn.com/problems/jump-game/solution/55-tiao-yue-you-xi-by-tonngw-ec5n/) | 动态维护并更新当前能达到的“最远边界” |
| [56. 合并区间](https://leetcode-cn.com/problems/merge-intervals) | [题解](https://leetcode-cn.com/problems/merge-intervals/solution/tong-su-yi-dong-xiang-jie-tan-xin-jing-d-ielv/) | 按区间左端点排序，然后贪心合并重叠部分 |
| [406. 根据身高重建队列](https://leetcode-cn.com/problems/queue-reconstruction-by-height) | [题解](https://leetcode-cn.com/problems/queue-reconstruction-by-height/solution/406-gen-ju-shen-gao-zhong-jian-dui-lie-b-08mz/) | 先按身高从高到矮排序，再根据 $k$ 值插入对应索引位置 |
| [621. 任务调度器](https://leetcode-cn.com/problems/task-scheduler) | [题解](https://leetcode-cn.com/problems/task-scheduler/solution/by-tonngw-f92t/) | 优先安排频次最高的任务，计算冷却时间插值 |
| [581. 最短无序连续子数组](https://leetcode-cn.com/problems/shortest-unsorted-continuous-subarray) | [题解](https://leetcode-cn.com/problems/shortest-unsorted-continuous-subarray/solution/by-tonngw-wedk/) | 线性双向扫描，寻找破坏单调性的最左和最右边界 |
| [253. 会议室 II](https://leetcode-cn.com/problems/meeting-rooms-ii) | 「会员题」 | 使用小顶堆维护当前所有进行中会议的结束时间 |

### 13. 脑筋急转弯与特殊递推
| 题目 | 题解 | 核心点 |
| ---- | ---- | ---- |
| [31. 下一个排列](https://leetcode-cn.com/problems/next-permutation) | [题解](https://leetcode-cn.com/problems/next-permutation/solution/31-xia-yi-ge-pai-lie-by-tonngw-f49c/) | 从后往前找第一个降序点，交换后逆序后半段（纯逻辑推理） |

### 14. 动态规划（DP：终极状态转移玄学）
按照递进难度重排，不要按原本的顺序硬啃：

| 题目 | 题解 | 分类与难点 |
| ---- | ---- | ---- |
| [70. 爬楼梯](https://leetcode-cn.com/problems/climbing-stairs) | [题解](https://leetcode-cn.com/problems/climbing-stairs/solution/70-pa-lou-ti-wan-quan-bei-bao-fei-bo-na-p7wwt/) | 基础递推（斐波那契模型） |
| [121. 买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock) | [题解](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/solution/by-tonngw-ky6p/) | 记录历史最低价，更新今日最大利润 |
| [53. 最大子数组和](https://leetcode-cn.com/problems/maximum-subarray) | [题解](https://leetcode-cn.com/problems/maximum-subarray/solution/53-zui-da-zi-xu-he-by-tonngw-9jx5/) | 若前一日连续和小于0，则断尾求生重新开始 |
| [62. 不同路径](https://leetcode-cn.com/problems/unique-paths) | [题解](https://leetcode-cn.com/problems/unique-paths/solution/62-bu-tong-lu-jing-by-tonngw-fczx/) | 二维网格递推：`dp[i][j] = dp[i-1][j] + dp[i][j-1]` |
| [64. 最小路径和](https://leetcode-cn.com/problems/minimum-path-sum) | [题解](https://leetcode-cn.com/problems/minimum-path-sum/solution/by-tonngw-egbd/) | 二维网格最值：`dp[i][j] = min(上, 左) + grid[i][j]` |
| [152. 乘积最大子数组](https://leetcode-cn.com/problems/maximum-product-subarray) | [题解](https://leetcode-cn.com/problems/maximum-product-subarray/solution/by-tonngw-3yk5/) | 乘法含负负得正，需要同时维护当前最大值和最小值 |
| [198. 打家劫舍 / 337. 打家劫舍 III](https://leetcode-cn.com/problems/house-robber-iii) | [题解](https://leetcode-cn.com/problems/house-robber-iii/solution/337-da-jia-jie-she-iii-by-tonngw-mg1f/) | 状态不相邻约束：选或不选。III为树形DP |
| [221. 最大正方形](https://leetcode-cn.com/problems/maximal-square) | [题解](https://leetcode-cn.com/problems/maximal-square/solution/by-tonngw-b99t/) | 受限于左、上、左上三方中的短板：`min(三者) + 1` |
| [300. 最长递增子序列](https://leetcode-cn.com/problems/longest-increasing-subsequence) | [题解](https://leetcode-cn.com/problems/longest-increasing-subsequence/solution/300-zui-chang-di-zeng-zi-xu-lie-by-tonng-0mvw/) | 经典 $O(n^2)$ 状态转移，可配合二分优化到 $O(n \log n)$ |
| [139. 单词拆分](https://leetcode-cn.com/problems/word-break) | [题解](https://leetcode-cn.com/problems/word-break/solution/139-dan-ci-chai-fen-by-tonngw-jiaf/) | 字符串分割，背包问题变形 |
| [279. 完全平方数](https://leetcode-cn.com/problems/perfect-squares) | [题解](https://leetcode-cn.com/problems/perfect-squares/solution/by-tonngw-37c0/) | 完全背包模型：凑齐数字所需的最少平方数数量 |
| [416. 分割等和子集](https://leetcode-cn.com/problems/partition-equal-subset-sum) | [题解](https://leetcode-cn.com/problems/partition-equal-subset-sum/solution/416-fen-ge-deng-he-zi-ji-by-tonngw-1w3h/) | 01背包模型：能否恰好装满总和一半的背包 |
| [494. 目标和](https://leetcode-cn.com/problems/target-sum) | [题解](https://leetcode-cn.com/problems/target-sum/solution/494-mu-biao-he-by-tonngw-nmoe/) | 转化为01背包的方案数求和问题 |
| [309. 最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown) | [题解](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/solution/zhuang-tai-ji-dp-309-zui-jia-mai-mai-gu-dylw4/) | 状态机 DP：持有、冷冻、不持有状态切换 |
| [72. 编辑距离](https://leetcode-cn.com/problems/edit-distance) | [题解](https://leetcode-cn.com/problems/edit-distance/solution/72-bian-ji-ju-chi-by-tonngw-2jch/) | 双字符串匹配经典模型：增、删、改的操作代价递推 |
| [10. 正则表达式匹配](https://leetcode-cn.com/problems/regular-expression-matching) | [题解](https://leetcode-cn.com/problems/regular-expression-matching/solution/by-tonngw-s42i/) | 困难题。双字符串匹配，重点处理 `*` 的零次或多次匹配 |
| [32. 最长有效括号](https://leetcode-cn.com/problems/longest-valid-parentheses) | [题解](https://leetcode-cn.com/problems/longest-valid-parentheses/solution/gua-hao-xu-lie-wen-ti-xiang-jie-han-xian-h7rn/) | 困难题。利用 DP 记录以当前右括号结尾的最长有效长度 |
| [312. 戳气球](https://leetcode-cn.com/problems/burst-balloons) | [题解](https://leetcode-cn.com/problems/burst-balloons/solution/by-tonngw-udnz/) | 顶级困难题。区间 DP，反向思考最后一个被戳破的气球 |
