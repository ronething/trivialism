<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [人工智能复习2018](#%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E5%A4%8D%E4%B9%A02018)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 人工智能复习2018

__更新于 2018/06/21__

__今天考试了__

__题目基本都是(90分左右)复习题里面的。__

__题目基本都是(90分左右)复习题里面的。__

__题目基本都是(90分左右)复习题里面的。__

---

- 复习题

---

`是非判断题` 正确题目

消解时主要通过推导空子句来实现反证的。

L、¬L 为互解文字，L∧¬L→□

极小极大分析法中采用逆向推算来计算节点得分的。

希望解树一定代价最小。

本原问题即直接可解的简单问题。

与或树搜索可分为盲目搜索和启发式搜索。

语义网络是一种有向图，它有5 个级别，7 种类型。

![](https://ws1.sinaimg.cn/large/bdc70b0agy1fshyae3rt2j20ni0ekk1y.jpg)

对象与类是实例关系。

基于语义网络的推理主要有网络匹配、网络继承和网络演绎三种
方式。

对“与”、“或”、“蕴含”关系，在语义网络表示时主要加上
“与”、“或”、“蕴含”结点。

框架之间也有从属关系、实例关系等。

网络环境下的专家系统结构可以分为客户机/服务器或浏览器/
服务器结构。

黑板模型中的黑板就是一个全局数据库。

人可以作为Agent。

智能计算与人工智能有很大关系。

神经网络是人工智能的联接主义倡导的模式。

进化计算中的遗传算法 $$SGA=(C,E,P_{0},M,\phi ,\tau ,\varphi,T)$$。

BP神经网络算法至少需要2层神经元。一层是输入层，一层是输出层。

ID3算法的目的是构造一棵树。树的根节点为分类开始。叶节点是实例。中间节点是属性，边是属性的值。

MP模型是1943年心理学家$W.McCulloch$和数理学家$W.Pitts$提出的模型。

神经网络模型中，激发函数若采用S型（Simoid）。主要针对神经元的饱和特性。

前馈网络和反馈网络最大的区别是：非循环链接模式。~~即输入和输出在一个神经元。~~

遗传算法中采用一定的编码表达种群中个体的染色体。

RS中信息系统是一个四元组$$（U，A，V，f）$$。

等价类即每一个元素不分明关系。

深度优先具有搜索空间的复杂度低，非最优的，非完备。

有界深度优先就是深度优先，只是增加了一个深度限制，非完备非最优。

迭代深度优先避免了给定深度带来的深度优先的缺陷，采用试探深度的方式确定树的深度。但是给策略是完备的且最优。

启发式搜索A算法是完备的且最优的。

当$$h(x)$$是单调性时，$$A^{*}$$算法转换为改进的$$A^{*}$$算法。

启发的与或树搜索算法成为AO*算法。

所有的等价类是基于不分明关系的。

粗糙集与模糊集的最大差别是模糊集~~为~~未真正解决“含糊”问题。即计算出具体的含糊元素数目。

粗糙集理论：首先构造等价关系，从而将集合划分为若干个等价类。然后通过上近似与下近似构成不确定边界区域，从而形成粗糙集。

当$$BN_{B}(x)\neq \phi $$时，称$$BN_{B}(x)$$ 是对象集X关于属性集B的粗糙集。

属性约简，是消除决策表中不必要的属性。因此定义$$b \in B$$,若$$IND(B) = IND(B-\{b\})$$，则b在B中是不必要的。

神经网络中激励函数主要有四种类型，其中最为常用的Sigmoid函数$$f(x)=\frac{1}{1+e^{-x}}$$ 。

<u>单层</u>感知器模型有两层构成，分别是输入层和输出层。

1986年PDP模型：（1）一组处理单元；（2）单元集合的激活状态；（3）各个单元的输出函数；（4）单元之间的连接模式；（5）通过连接网络传送激活模式的传递规则；（6）把单元输入和她的当前状态结合起来，以产生新激活值得激活规则；（7）通过经验修改连接模式的学习规则；（8）系统运行的环境。

命题逻辑语句的可满足判定是SAT问题，是一个被证明为NP完全的问题。

粗糙集是指边界区域不为空集的区域。

---

`是非判断题` 错误题目

$$(P(x) ∧Q(y))∨(P(x) ∧R(y))$$为合取范式。（应为析取范式）

若$$P(x)$$为时真时假，则$$P(x)$$仍为永真式。（应为可满足式）

$$\forall x((p(x)\vee R(x))$$中的$$P(x)$$不在x 的辖域中。

对 α-β 剪枝技术中，对与节点来说，α 是倒推值的下确界，β 是倒推
值的上确界。（α为上确界，β为下确界）

方位关系不在语义网络表示的范围内。（在，书里p36）

专家系统是由数名专家组成的咨询系统。（专家系统是一种模拟人类专家解决领域问题的计算机程序系统。）

用普通的程序设计语言开发专家系统的开发周期最长，效率最
低，但限制最小。

智能机器人的智能已经达到人类智能的水平。

遗传和变异是生物进化的两种基本现象。所以遗传算法只有两个算子：变异算子和遗传算子。（p112 选择算子 交叉算子 变异算子）

决策树学习不是一种以示例为基础的归纳学习方法。

单层感知器学习是一种基于规则的学习。

![](http://pa58zqlgq.bkt.clouddn.com/20180612210607.png)

AI、BI、CI是完全独立的不同的三种智能。（计算智能是智力的低层认知，主要取决于数值数据而不依赖于知识。人工智能是在计算智能的基础上引入知识而产生的智力中层认知。生物智能，尤其是人类智能，则是最高层的智能。即CI包含AI包含BI）

若两个个体分别表达为：001101和110010，若随机交叉点为3和5（自左向右数），则交叉后的新个体为：001010和110101。

> 书本p118
>
> - 单点交叉
>
> 随机算则第k位为交叉点，若采用对交叉点后面的基因进行交换方法，单点交叉是将X中的$$x_{k+1}$$到$x_{n}$部分与$Y$中的$y_{k+1}$与$y_{n}$部分进行交叉，交叉后生成的两个新的个体是：
>
> $X^{'}=x_{1}x_{2}...x_{k} y_{k+1}...y_{n}$
>
> $Y^{'}=y_{1}y_{2}...y_{k} x_{k+1}...x_{n}$
>
> - 两点交叉
>
> 随机设定第i,j位为两个交叉点（其中i<j<n），两点交叉是将$X$中的$x_{i+1}$到$X_{j}$部分与$Y$中的$y_{i+1}$到$y_{j}$部分进行交换，交叉后生成的两个新的个体是：
>
> $X^{'}=x_{1}x_{2}...x_{i} y_{i+1}...y_{j} x_{j+1}...x_{n}$
> 
> $Y^{'}=y_{1}y_{2}...y_{i} x_{i+1}...x_{j} y_{j+1}...y_{n}$

（于是 001101和110010 若随机交叉点为3和5 则交叉后的两个新的个体001011和110100。）

在模糊集中，通常用隶属度刻画每个元素映射为(0,1)上的一个值。（不是(0,1)，是[0,1]）

若两个模糊集合F、G，则可以进行交、并、补等运算。（必须是$$U$$(论域)上的两个模糊集）

下近似比上近似的元素个数少。（应该是不能确定）

粗糙集就是边界区域。

![](http://pa58zqlgq.bkt.clouddn.com/20180612212204.png)

不分明关系与分明矩阵具有很强的相关性。（貌似并没有）

A算法只有在$$h(x)\leq h^{*}(x)$$的限制下才转换为A\*算法。（书里p84 还有一个是$$g(n)>0$$）

所有的边界区域与粗糙集是完全等价的。

定义$$X \subseteq U, A \subseteq B$$，对象集X关于属性集B的边界区域定义为：$$BN_{B}(x)=B^{-}(X)-B_{-}(X)$$ 。 （貌似错在$$A \subseteq B$$，书里p130定义是$$B \subseteq A$$）

---

`是非判断题` ~~未确定~~ 答案正确

$$(A \Leftrightarrow B)\wedge(\sim A \vee B)$$是可满足的 （应该是正确的。前面$$(A \Leftrightarrow B)$$为重言式，后面也是成立的）

---

- 计算题

2、用语义网络和框架方法表示下属知识

（1）John gives a book to Mary

![](http://pa58zqlgq.bkt.clouddn.com/20180614013952.png)

> 基本的语义关系：
>
> ISA 实例关系 Is-a 例如题目中John is a human
>
> AKO 分类关系 例如鸟是一种动物
>
> 成员关系 A-Member-of 例如张强是共青团员
>
> 属性关系 Have Can Age 例如鸟有翅膀 张强18岁
>
> 包含关系（也称为聚类关系）Part-of 例如大脑是人体的一部分
>
> 时间关系 Before After 例如 伦敦奥运会在北京奥运会之后
>
> 位置关系 Located-on at under inside outside 例如书在桌子上
>
> 相似关系 Similar-to Near-to 例如猫似虎

（2）高老师从3 月到7 月给计算机系学生讲《计算机网络》课。

![](http://pa58zqlgq.bkt.clouddn.com/20180614014753.png)

（3）创新公司在科海大街56 号，刘洋是该公司的经理，他32 岁、硕士学位。

![](http://pa58zqlgq.bkt.clouddn.com/20180614015036.png)

归结式（课本P60）

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsgjhoyrfvj20x607tgms.jpg)

子句集的化简

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsgjupphltj20mf0lntb9.jpg)

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsgljcyw8yj20va0h67a6.jpg)

博弈树 α-β 剪枝

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fshmhjusxuj20ze0k9gpy.jpg)

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fshmiiyr6cj20rc0f979s.jpg)



---

- 以下为知识点

---

- 范式

  （1）由有限个简单合取式构成的析取式称为析取范式。
  （2）由有限个简单析取式构成的合取式称为合取范式。
  （3）析取范式与合取范式统称为范式。

- 蕴含式

![](http://pa58zqlgq.bkt.clouddn.com/20180612191852.png)

- 一字棋极大/极小过程

![](http://pa58zqlgq.bkt.clouddn.com/20180612190523.png)

---

- 第三章

```
搜索的类型
# 按是否使用启发式信息：    
- 盲目搜索：按预定的控制策略进行搜索，在搜索过程中获得的中间信息并不改变控制策略。     
- 启发式搜索：在搜索中加入了与问题有关的启发性信息，用于指导搜索朝着最有希望的方向前进，加速问题的求解过程并找到最优解。
# 按问题的表示方式：
- 状态空间搜索：用状态空间法来求解问题所进行的搜索 
- 与或树搜索：用问题归约法来求解问题时所进行的搜索
```

> 状态空间问题表示
>
> - 状态
> - 操作
> - 状态空间 可用一个三元组$$(S,F,G)$$表示，S为问题的所有初始状态的集合，F为操作的集合，G为目标状态的集合。也可用一个赋值的有向图表示，节点表示问题的状态，有向边表示操作。

问题归约为子问题时，可采用对原问题进行分解或变换的方法。

所谓本院问题是指那种不能（或不需要）再进行分解或变换，且可以直接解答的问题。本原问题可以作为终止归约的限制条件。

- 与/或树表示

![](http://pa58zqlgq.bkt.clouddn.com/20180614110142.png)

与树有小弧线，或树没有。

端节点不一定是终止节点，如果不是终止节点，就是不可解节点，终止节点都是可解节点。

解树：由可解节点构成，并且由这些可解节点可以推出初始节点（它对应着原始问题）为可解节点的子树为解树。

> 问题归约求解过程就实际上就是生成解树，即证明原始节点是可解节点的过程。

状态空间的盲目搜索

- 广度优先搜索：先生成的节点先拓展 只要问题有解，就一定可以找到 且为最优解 
- 深度优先搜索：后生成的节点先拓展  可能找不到最优解 或者找不到解 解决方法：增加深度限制

代价树的盲目搜索

- 代价树的广度优先搜索
- 代价树的深度优先搜索

状态空间的启发式搜索

- 启发性信息：指那种与具体问题求解过程有关的，并可指导搜索过程朝着最有希望方向前进的控制信息。
- 估价函数：用来估计节点重要性，定义为从初始节点$S_{0}$出发，约束经过节点n到达目标节点$S_{g}$的所有路径中最小路径代价的估计值。一般形式：             $f(n)=g(n)+h(n)$ 其中，$g(n)$是从初始节点$S_{0}$到节点$n$的实际代价；$h(n)$是从节点$n$到目标节点$S_{g}$的最优路径的估计代价。 
- $h(n)$也称为启发函数

---

第 4 章 计算智能

- AI，BI，CI
  - ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsdl5k2ej3j20wg0o5t9y.jpg)

- MP模型是美国心理学家麦克洛奇(W.McM  ulloch)和数理逻辑学家皮茨(W.Pitts) 根据生物神经元的功能和结构，于1943年提出的一种将神经元看作二进制阈值元件的简单模型。

- 常用的人工神经元模型
  - 阈值型(Threshold)
  - 分段线性强饱和型(Linear  Saturation)
  - S型(Sibmoid)
  - 子阈累积型(Subthreshold  Summation)

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsdldvbwe4j20wa0o2762.jpg)

- 多层前馈网络的典型代表是BP网络。

- 一个神经网络的隐含层越多，其复杂度就会越高。

- 反馈网络的典型代表是 Hopfield 网络模型。

- 所谓反馈联结方式是指一个神经元的输出可以被反馈至同层或前层的神经元。

- 单层感知器是一种只具有单层可计算节点的前馈网络。

- 多层感知器是通过在单层感知器的输入、输出层之间加入一层或多层处理单元所构成的。其拓扑结构与多层前馈网络相似。

- BP网络模型：多层前馈网络

- Hopfield网络模型：单层全互联的对称反馈网络模型。

- 离散 Hopfield 网络和连续 Hopfield 网络。

- 离散 Hopfield 模型的稳定性： $x(t)$ 表示网络在时刻t的状态，$t=0$ 时，网络的状态就是由输入模式确定的初始状态。如果从某一时刻$t$开始存在一个有限的时间$\Delta t$，网络的状态不再发生变化，即 $x(t+\Delta t)=x(t)$ $(\Delta t>0)$ 则称网络是稳定的。

- 进化计算主要包括以下四大分支：

  - 遗传算法（Genetic Algorithm，GA）
  - 进化策略（Evolutionary Strategy，ES）
  - 进化规划（Evolutionary Programming，EP）
  - 遗传规划（Genetic Programming，GP）

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsegbx33eoj20uy0fdmye.jpg)

- 自然界生物进化过程是进化计算的生物学基础，它主要包括遗传(Heredity)、变异(Mutation)和进化(Evolution)理论。

- 与传统算法相比，进化计算具有以下优良特征：

  - 自组织性
  - 自适应性
  - 并行性
  - 多解性
  - 全局优化性
  - 内在学习性
  - 统计性
  - 稳健性

- 标准的遗传操作包括以下3种基本形式：  

  - 选择（Selection）
  - 交叉（Crossover）  
  - 变异（Mutation）

- 遗传算法可形式化地描述为 $GA=(P(0),N,l,M,s,g,P,f,T)$  

  - $P(0)=\{P_{1}(0),P_{2}(0),..,P_{n}(0)\}$ 表示初始种群
  - $N$ 表示种群规模
  - $l$ 表示编码串的长度
  - $s$ 表示选择策略
  - $g$ 表示遗传算子，它包括选择算子$Q_{r}$、交叉算子$Q_{c}$和变异算子$Q_{m}$
  - $P$ 表示遗传算子的操作概率，它包括选择概率$P_{r}$、交叉概率$P_{c}$和变异概率$P_{m}$
  - $f$ 是适应度函数
  - $T$ 是终止标准

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsehhleifmj20t10ifdgq.jpg)

- 二进制编码

- 格雷编码 模2加法和异或等同。1+1=0+0=0 1+0=0+1=1

- 实数编码

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fseozbaovdj20rg0h0ju3.jpg)

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsei64xvgrj20ve0jx0vi.jpg)

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fseie2ud1wj20vk0hsq4i.jpg)

- 基本遗传算法操作：

  - 选择
  - 交叉
  - 变异

- 选择操作

  - 比例选择
    - 轮盘赌选择
    - ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fseijannp4j20va0ivwgj.jpg)
    - 繁殖池选择
    - 排序选择（不常用）
    - 竞技选择（不常用）

- 交叉操作

  - 根据个体编码方法的不同，可以分为如下两种：
    - 二进制交叉 主要包括单点交叉，两点交叉。多点交叉和均匀交等方法。单点交叉和多点交叉前面复习题有提到。
      - 多点交叉
      - ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsej12gvfnj20wf0jr416.jpg)
      - 均匀交叉
      - ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsej30nq9tj20w10jz40p.jpg)
    - 实值交叉 
      - 离散交叉
        - 部分离散交叉
        - 整体离散交叉
      - ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsej7nokabj20vg0jrtbw.jpg)
      - 算术交叉

- 变异操作

  - 二进制值变异
  - ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsejakfrtcj20ug08rgmp.jpg)
  - 实值变异
  - 基于位置的变异
  - 基于次序的变异
  - ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsejcqdnsuj20v80dvdhn.jpg)

---

- 模糊集的定义（隶属函数的概念 U论域的范围 [0,1]）
- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfkuxez12j20vo0hp409.jpg)
- 模糊集的表示
- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfl2hr8xcj20vz0j6wg8.jpg)
- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfl2tgzi5j20vm0h6js8.jpg)
- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfqde8fmhj20v20ikq4o.jpg)
- 记住加号不是加号，''/''不是除号，$\int $不是数学中的积分符号，他们只是为了表示模糊集而设定出来的一些符号而已。
- 模糊集的运算
- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfqe5ceapj20v40jewg8.jpg)
- 定义4.4 为叙述简便，模糊集合论中通常用“$\vee$”代表max，“$\wedge $”代表min，即有

  $F\cup G_{:\mu F\cup G}(u)=\mu F(u)\vee \mu G(u)$
  $F\cap G_{:\mu F\cap G}(u)=\mu F(u)\wedge \mu G(u)$
- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsflv6vwg9j20vr0ko0ul.jpg)
- 模糊关系的合成（见上图）注意先$\wedge$ 再$\vee$ 图中例子：

  $R(1,1)=(0.4\wedge0.7)\vee(0.5\wedge0.2)\vee(0.6\wedge0.5)=0.4\vee0.2\vee0.5=0.5$
- 模糊变换
- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfm1puyhtj20uu0j4gmj.jpg)

---

- 粗糙集（Rough Set，RS）

- 模糊逻辑并未能真正解决“含糊”问题。

- 信息系统: 信息系统是RS理论研究的主体，它被抽象为一个数据集，即一张数据表。

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfmfmydxdj20vy0igwft.jpg)

- 不分明关系 

- 等价类 

- 等价划分（等价类的集合），记为$U/IND(B)$或者$U/B$。

- 上近似和下近似

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfmr35g1nj20vg0jpmzk.jpg)

- 边界区域和粗糙集

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfmxfvdbdj20vj0ih406.jpg)

- 决策表的约简：决策表约简是指化简决策表中的条件属性和属性值，使得决策表在保持决策能力的同时，具有较少的条件属性和属性值。    

- 所谓决策能力，是指分类能力，即依据条件属性值，判别对象的类属。 

- 决策表的约简的过程
  - 一致性检查
  - 条件属性约简
  - 属性值约简

- 一致性检查：

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfnwr5181j20vb0kggn6.jpg)

- 条件属性的约简：属性约简实际上就是要消去决策表中某些不必要的列。其概念主要包括属性的必要性、属性集的约简、约简核、分明矩阵等。 

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfo3oe1vjj20un0g3q4g.jpg)

- 分明矩阵

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfo4jc58tj20v60aiab1.jpg)

- 约简核 *分明矩阵*中所有只包含单一属性元素的矩阵项的集合，即

  $CORE(A)=\{ a\in A | m_{ij}=\{ a \}, i, j=1, 2 , … , n \}$

- 约简核需要扩充

  上述生成的约简核，往往不是相应属性集的约简，原因是生成过程会丢失一些不能来自单属性元素的必要属性。因此，必须经过适当扩充，才能生成约简。

- 约简核扩充的方法
  ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfoche0f4j20us0du76b.jpg)

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfoehcqmwj20v80jemzb.jpg)

- 属性值的约简

  由于决策表的每一行都可看做一条决策规则，因此属性值约简就是约简决策规则。

  消除重复行，然后确定每行条件属性的核值，最后再约简每一行。

- 消除重复行，

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfoihe1zrj20uf0hi74m.jpg)

- 消除重复行后

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfoq6n3skj20uw0hzt9u.jpg)

- 确定每行条件的核值

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfoqq2dynj20ux0jwabo.jpg)

- 约简每一行

- ![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fsfop5d3lmj20uy0jkac1.jpg)


---

第二章

- 自然演绎推理

- 置换

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fshmscvfovj20ui0gujso.jpg)

- 摩根定律

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fshmxo1ndgj208t02kgln.jpg)

- 量词转换律

![](https://ws1.sinaimg.cn/large/ecb0a9c3gy1fshnl9gnozj20lx0chq7z.jpg)

- 子句集及化简（课本P56-P58）

  - 原子谓词公式及其否定统称为文字。
  - 任何文字的析取式称为子句。
  - 不包含任何文字的子句称为空子句。
  - 由子句或空子句所构成的集合称为子句集。

    - 消去连接词"->"和"<->"
    - 减少否定符号的辖域
    - 对变元标准化
    - 化为前束范式
    - 消去存在量词
    - 化为 Skolem 标准形
    - 消去全称量词
    - 消去合取词
    - 更换变元名称

- 归结式$C_{12}$是其亲本子句$C_{1}$和$C_{2}$的逻辑结论。

