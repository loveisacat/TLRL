# Paper Collection of Reinforcement Learning with Transfer Ability

Combine transfer learning into reinforcement learning is a hot and interesting field.

The Survey part includes two highly related surveys, one is focused on Single-agent RL, and another is focus on Multiagent RL.

The SMAC-based part is all papers based on "The StarCraft Multi-Agent Challenge" in recent years(2018-2021).

The State/Action Representation part is about the representation work in RL.

The Papers are sorted by time. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact Bin Chen (Email: chenbin15@sina.com).

## Content
* [Survey](#survey)  
* [SMAC-based](#smac-based)  
* [State/Action Representation](#representation)  
* To be continued ...



## Survey  
* [Transfer Learning in Deep Reinforcement Learning: A Survey](https://arxiv.org/pdf/2009.07888.pdf) by Zhuangdi Zhu, Kaixiang Lin, and Jiayu Zhou. 2021 
* [A Survey on Transfer Learning for Multiagent Reinforcement Learning Systems](https://jair.org/index.php/jair/article/view/11396/26482) by Felipe Leno Da Silva,Anna Helena Reali Costa. JAIR, 2019 [中文翻译](https://blog.csdn.net/caozixuan98724/article/details/107525332)

## SMAC-based  
* [The Surprising Effectiveness of MAPPO in Cooperative, Multi-Agent Games](https://arxiv.org/abs/2103.01955) by Chao Yu, etc.  
* [Cooperative Multi-Agent Transfer Learning with Level-Adaptive Credit Assignment](https://arxiv.org/pdf/2106.00517.pdf) by Tianze Zhou, etc.  
* [Multi-Agent Collaboration via Reward Attribution Decomposition](https://arxiv.org/abs/2010.08531) by Tianjun Zhang, etc. ICLR 2021. [知乎解读](https://zhuanlan.zhihu.com/p/271648948)  
* [UPDET: UNIVERSAL MULTI-AGENT REINFORCEMENT LEARNING VIA POLICY DECOUPLING WITH TRANSFORMERS](https://openreview.net/pdf/1f24b0b3a09ad8484d3887053d6c4c6a87d96ba1.pdf) by Siyi Hu etc. ICLR 2021. 
* [TRANSFER AMONG AGENTS: AN EFFICIENT MULTIAGENT TRANSFER LEARNING FRAMEWORK](https://arxiv.org/pdf/2002.08030.pdf) by TianPei Yang. 2021.  
* [From Few to More: Large-Scale Dynamic Multiagent Curriculum Learning](https://ojs.aaai.org/index.php/AAAI/article/view/6221) by Weixun Wang etc. AAAI 2020. 
* [Multi-Agent Game Abstraction via Graph Attention Neural Network](https://arxiv.org/pdf/1911.10715.pdf) by Yong Liu etc. AAAI 2020.  
* [RODE: Learning Roles to Decompose Multi-Agent Tasks](https://arxiv.org/pdf/2010.01523.pdf) by Tonghan Wang etc. 2020.  
* [Transfer Learning Between RTS Combat Scenarios Using Component-Action Deep Reinforcement Learning](https://skatgame.net/mburo/aiide20ws/papers/paper4-cameraready.pdf) by Richard Kelly etc. 2020.  
* [Adaptive Average Exploration in Multi-Agent Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/9256721) by Garrett Hall etc. 2020.  
* [Multi-Agent Feature Learning and Integration for Mixed Cooperative and Competitive Environment](https://ieeexplore.ieee.org/abstract/document/9288288) by Yaowen Zhang etc. ICTAI 2020.  
* [Deep Coordination Graphs](http://proceedings.mlr.press/v119/boehmer20a/boehmer20a.pdf) by Wendelin Bohmer,Vitaly Kurin,Shimon Whiteson. ICML 2020.  
* [ROMA: Multi-Agent Reinforcement Learning with Emergent Roles](http://proceedings.mlr.press/v119/wang20f/wang20f.pdf) by Tonghan Wang etc. ICML 2020.  
* [Multi-Agent Determinantal Q-Learning](http://proceedings.mlr.press/v119/yang20i/yang20i.pdf) by Yaodong Yang etc. ICML 2020.  
* [QPLEX: DUPLEX DUELING MULTI-AGENT Q-LEARNING](https://arxiv.org/pdf/2008.01062.pdf) by Jianhao Wang etc. 2020.  
* [Towards Heterogeneous Multi-Agent Reinforcement Learning with Graph Neural Networks](https://arxiv.org/pdf/2009.13161.pdf) by Douglas R. Meneghetti etc. 2020.  
* [The Emergence of Individuality in Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2006.05842.pdf) by Jiechuan Jiang etc. 2020.  
* [Shared Experience Actor-Critic for Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2006.07169.pdf) by Filippos Christianos etc. 2020.  
* [RIIT: Rethinking the Importance of Implementation Tricks in Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2102.03479.pdf) by Jian Hu etc. 2020.  
* [Is Independent Learning All You Need in the StarCraft Multi-Agent Challenge?](https://arxiv.org/pdf/2011.09533.pdf) by Christian Schroeder de Witt etc. 2020.  
* [Rethinking Intelligent Behavior as Competitive Games for Handling Adversarial Challenges to Machine Learning](https://link.springer.com/chapter/10.1007/978-3-030-55692-1_1) by Joseph B etc. Adversary-Aware Learning Techniques and Trends in Cybersecurity 2020.  
* [BENCHMARKING MULTI-AGENT DEEP REINFORCEMENT LEARNING ALGORITHMS](https://www.researchgate.net/profile/Chao-Yu-53/publication/349943157_Benchmarking_Multi-agent_Deep_Reinforcement_Learning_Algorithms/links/60482fff4585154e8c8accb1/Benchmarking-Multi-agent-Deep-Reinforcement-Learning-Algorithms.pdf) by Chao Yu etc. 2020.  
* [StarCraft Micromanagement with Reinforcement Learning and Curriculum Transfer Learning](https://arxiv.org/pdf/1804.00810.pdf) by Kun Shao etc. IEEE Transactions on Emerging Topics in Computational Intelligence 2019. 
* [Graph Embedding Priors for Multi-task Deep Reinforcement Learning](http://128.148.32.110/people/gdk/pubs/graph_embed_deeprl_ws.pdf) by Neev Parikh etc. 2020.  
* [The StarCraft Multi-Agent Challenge](https://arxiv.org/pdf/1902.04043v1.pdf) by Mikayel Samvelyan etc. 2019.  
* [LIIR: Learning Individual Intrinsic Reward in Multi-Agent Reinforcement Learning](https://proceedings.neurips.cc/paper/2019/file/07a9d3fed4c5ea6b17e80258dee231fa-Paper.pdf) by Yali Du etc. NIPS 2019  
* [Exploration with Unreliable Intrinsic Reward in Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1906.02138.pdf) by Wendelin Bohmer etc. 2019.  
* [MAVEN: Multi-Agent Variational Exploration](https://arxiv.org/pdf/1910.07483.pdf) by Anuj Mahajan etc. 2019.  
* [Learning to Teach in Cooperative Multiagent Reinforcement Learning](https://arxiv.org/pdf/1805.07830.pdf) by Shayegan, AAAI 2019.  
* [Multi-Agent Common Knowledge Reinforcement Learning](https://arxiv.org/pdf/1810.11702.pdf) by Christian A etc. 2018. 
## State/Action Representation
* [Decoupling Value and Policy for Generalization in Reinforcement Learning](https://arxiv.org/pdf/2102.10330.pdf) by Roberta Raileanue etc. 2021. 

