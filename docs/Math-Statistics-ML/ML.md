# Machine Learning


## Books
- [x] [Introduction to Data Mining](https://www-users.cs.umn.edu/~kumar001/dmbook/index.php)

    ??? "数据挖掘导论"
        中文书名为《数据挖掘导论》，翻译的是第一版，现在又出了英文第二版。内容比较丰富，比较适合入门（因为书籍并没有刻意避开复杂的地方，所以也并没有很简单）。



- [x] [Learning From Data](https://work.caltech.edu/library/index.html)

    ??? "高屋建瓴之神作"
        如果从看过的机器学习书籍中

- [x] [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)

    ??? "NNDL: 个人看来入门DL最好(没有之一)的一本书"
         先是从理论上把基于梯度下降的优化过程讲清楚，之后写代码从零开始构建神经网络。条理清晰，层次分明，没有回避任何问题，读完解决了很多之前一直都有的疑惑。

- [x] [Neural Networks from Scratch in Python](https://nnfs.io/)

    ??? "NNFS: 从零实现神经网络"
        如果说Michael Nielsen的NNDL是高屋建瓴，站在足够的高度为读者展示整个NN的蓝图，那么这本NNFS就是踩在坚实的大地上，为读者提供蓝图中的每一处事物并带领你亲身去体验。其实NNDL本身也已经包含了很多NNFS提供的内容，但是后者更加具体一些。

        **优点**: From Scratch是透彻理解一个事物的最直接有效的办法，前提是真的From Scratch; NN的Forward部分讲的比较详细，逻辑清晰，代码简洁; 对Nonlinear(Activation function)的讲解细致，其中部分应该是参考了Michael Nielsen, Neural Networks and Deep Learning中[Chap4 A visual proof that neural nets can compute any function](http://neuralnetworksanddeeplearning.com/chap4.html) 的内容. 两者可以互为参考; Chap9 Backpropagation写的极为细致清晰，应该是我目前看到的最为清晰的BP讲解与实现，层层递进，引人入胜; Chap10 Optimizers算是差强人意，对各个优化器motivation的讲解较为清晰，代码写的也比较好.比较可惜的是没有放任何公式...这些公式又不难，贴上来对着代码讲一下会好很多; Chap18 Model Object， Chap21 Saving and Loading Models and Their Parameters都写的不错，条理清晰，代码也是一步步地讲解

        **缺点**:Chap6,7,8中对Calculus(Derivative, Gradient等)的讲解有些繁琐，且稍显粗浅; Chap11, 12, 13分三章讲Testing Data/Validation Data/Training Data, 每章几页草草了事，大可不必...不过能提到data leakage也算是弥补回来一点


- [ ] [Chapman & Hall/CRC Data Mining and Knowledge Discovery Series](https://www.crcpress.com/Chapman--HallCRC-Data-Mining-and-Knowledge-Discovery-Series/book-series/CHDAMINODIS?page=&order=pubdate&size=48&view=list&status=published,forthcoming)

    ??? "Data Mining技术的历史演进"
        此系列包括了CRC Press自2007年以来的数据挖掘方面的书籍，从最初的EXCEL, 到SAS，再到Python和R，进行着明显的演进。


## Courses
- [x] [Machine Learning(NYU, DS-GA 1003)](https://davidrosenberg.github.io/ml2019/#home)

    ??? "非常好的Machine Learning课程, 力荐!"
        这门课程没有回避任何问题，对优化问题作出了很好的解释和说明。而且课程是站在一个相当高的角度(基于Risk)来展开，很有启发性。课程资料及自己的习题解答放在Github: [NYU-ML](https://github.com/shenxiangzhuang/NYU-ML)

- [x] [CS-L,W-182/282A Designing, Visualizing and Understanding Deep Neural Networks(Berkeley, Spring 2020)](https://bcourses.berkeley.edu/courses/1487769/wiki)

    ??? "非常好的Deep Learning教程, 力荐!"

        (2021-02-28)做完了Assignment1, 几乎是完全从头开始搭建FC和CNN网络，走完整个流程对整个训练的过程有了相当深刻的认识，受益匪浅！

        (2021-03-15)这是一个近乎完美的课程！前三个Assignment是全部完成了的，在及其友好的引导下手写了CNN, Vanilla RNN, LSTM, Transformer等实现，通过写Forward和Backward的步骤，对各种网络结构的理解又加深了一个层次。

        这种from scratch的实现方式也是我最喜欢的方式——个人认为这是最为直观，有效的学习方式。这是因为from scratch的代码一方面可以让模糊的理论理解更加清晰，同时也提供了关于算法落地的insight。这些实现基本上没有加任何优化，所以运行效率都比较低，但是正因为如此才能够以一种更为直接的方式将算法本身的面目呈现出来。

        课程后半主要讲的是GAN和RL, 这块之前几乎没有接触过，所以学起来比较吃力。所以最后的Assignment4(RL相关)只做了一部分，还是参考了下面的实现写的。感觉这块内容进度有点太快了，也是因为我主要以Lecture Notes为主，资料看得比较少。


- [ ] [Introduction To Machine Learning](https://www.cs.huji.ac.il/~shais/IML2014.html)

    ??? 高屋建瓴

        这是根据*[Understanding Machine Learning: From Theory to Algorithms  ](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/index.html)*这本书找到的课程。

        这本书只看了开头几章，真的是高屋建瓴！而且对PAC理论的推导是我目前见过最为精彩而且容易懂的，所以打算把DS-GA 1003的完成度作为目标，配合课程，书籍，习题和答案将这learning theory这部分的理论补充起来！


- [ ] [Inference and Representation (NYU,DS-GA-1005, CSCI-GA.2569)](https://github.com/joanbruna/ir18)

    ??? 概率图模型

        和上面的DS-GA 1003一个的系列的课程，主要关注的是概率图模型。资料也很全，后面系统学习概率图时打算选此课作为引导。



- [ ] [Introduction to Machine Learning(CMU, 10-301 + 10-601)](https://www.cs.cmu.edu/~mgormley/courses/10601-s19/schedule.html)

    ??? Introduction级别好课程

        CMU的ML课程。对我而言比较熟悉的算法，比如Decision Tree,看这个课的lecture notes就感觉略简单了。但是一些不是很熟悉的算法如Reinforcement Learning这些，看这种Introduction级别的还是挺不错的。

- [ ] [Machine Learning and Statistical Pattern Recognition(CSE 5523)](http://aritter.github.io/courses/5523_fall18.html)

    ??? 参考课程

        在查Naive Bayes的MAP估计时查到了这门课，感觉NB算法的MAP估计讲的很透彻。

- [ ] [Introduction to Deep Learning(STAT 157, UC Berkeley, Spring, 2019)](https://courses.d2l.ai/berkeley-stat-157/index.html)

    ??? note "UC Berkeley的DL"

        D2L

- [ ] [Introduction to Deep Learning(Princeton, COS 495)](https://www.cs.princeton.edu/courses/archive/spring16/cos495/)

    ??? note "作为学习Deep Learning的参考"

        Princeton的其他AL&ML相关课程可以在[https://aiml.cs.princeton.edu/course.html](https://aiml.cs.princeton.edu/course.html) 找到。
        其中Mathematics for Numerical Computing and Machine Learning， Theoretical Machine Learning 看着还不错。

- [ ] [Mining Massive Data Sets(Stanford, CS246, Winter 2020)](http://web.stanford.edu/class/cs246/)

    ??? note "MMDS"

        聚焦算法的大规模工程部署, 很值得学的课程

- [ ] [Machine Learning & Data Mining(Caltech, CS 155, Winter 2020)](http://www.yisongyue.com/courses/cs155/2020_winter/)

    ??? note "Caltech机器学习"

        Lecture notes看着还不错


- [ ] [CS 189/289A-Introduction to Machine Learning](https://people.eecs.berkeley.edu/~jrs/189/)

    ??? note "Berkeley统计机器学习"

        理论讲的比较深入，给了很多有用的资料。（后面需要重点看的）


- [ ] [CSC2541 Winter 2021   Topics in Machine Learning:   Neural Net Training Dynamics](https://www.cs.toronto.edu/~rgrosse/courses/csc2541_2021/)

    ??? note "深入DL训练过程的"

        试图分析DL效果好的原因，值得好好看！

- [ ] [CSE 5526: Neural Networks, Fall 2014](http://mr-pc.org/t/cse5526/)

    ??? note "神经网络参考课程"

        看到说Simon那本*Learning Networks and Learning Machines*不错，就去找了下相关的课程，只找到了这个，感觉可以作为书的引导。


- [ ] [**CS224W: Analysis of Networks(Stanford)**, Fall2018](http://snap.stanford.edu/class/cs224w-2018/)

    ??? 图数据挖掘课程
        这里选择Fall2018出于两个目的：课程作业可以获取；有教学录制视频。

- [ ] [Graph Neural Networks](https://hhaji.github.io/Deep-Learning/Graph-Neural-Networks/)

    ??? "GNN最全总结"
        发现这位大佬教的课[https://hhaji.github.io/Teaching/](https://hhaji.github.io/Teaching/)
        真的都很顶！个人十分喜欢这种给出大量参考资料的课程！

- [ ] [CS 285 at UC Berkeley: Deep Reinforcement Learning](http://rail.eecs.berkeley.edu/deeprlcourse/)

    ??? "Berkeley DRL"
        目前用到DRL的场景很少，作为后续学习参考

- [ ] [Foundations of Machine Learning-Fall2020](https://cs.nyu.edu/~mohri/ml20/)

    ??? "硬核ML Foundation"
        书籍[Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/)作者开设的对应的课程

- [ ] [Machine Learning and Data Mining-CSC 411 Winter 2019](https://www.cs.toronto.edu/~mren/teach/csc411_19s/#overview)

    ??? "Toronto大学的机器学习课程"
     选录进入此系列是因为这个课程覆盖面较全，虽然较为精简。然后也有配套的homework。

## Blogs

- Apple: [Machine Learning Research at Apple](https://machinelearning.apple.com/)

- Amazon: [AWS Machine Learning Blog](https://aws.amazon.com/blogs/machine-learning/)

- Google: [Google Research](https://research.google/)

- Microsoft: [Microsoft Research](https://www.microsoft.com/en-us/research/publications/)

- Twitter: [Twitter Engineering](https://blog.twitter.com/engineering/en_us)

- Meta(Facebook): [AI Research](https://engineering.fb.com/category/ai-research/)

- Netflix: [Netflix TechBlog](https://netflixtechblog.com/)
