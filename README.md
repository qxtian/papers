# papers

## Offline RL
#### Model free
[OPAL: Offline Primitive Discovery for Accelerating Offline Reinforcement Learning](https://openreview.net/pdf?id=V69LGwJ0lIN)

[CQL: Conservative Q-Learning for offline reinforcement learning](https://arxiv.org/pdf/2006.04779.pdf)

[Is Pessimism Provably Efficient for Offline RL?](https://arxiv.org/pdf/2012.15085.pdf)

[THE IMPORTANCE OF PESSIMISM IN FIXED-DATASET POLICY OPTIMIZATION](https://arxiv.org/pdf/2009.06799.pdf)

[Off-Policy Deep Reinforcement Learning without Exploration](https://arxiv.org/pdf/1812.02900.pdf), BCQ, ICML 2019.

[Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://arxiv.org/pdf/1906.00949.pdf), BEAR, including analysis of OOD Actions in Q-Learning.

[Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/pdf/1911.11361.pdf), BRAC, generalizing BEAR, BCQ, etc.

[Critic Regularized Regression](https://arxiv.org/pdf/2006.15134.pdf), CRR, Nips 2020.

[Q-Value Weighted Regression: Reinforcement Learning with Limited Data](https://arxiv.org/pdf/2102.06782.pdf#page=10&zoom=100,0,0) An extension of [KEEP DOING WHAT WORKED ...], unaccepted. 

[Batch Reinforcement Learning Through Continuation Method](https://openreview.net/pdf?id=po-DLlBuAuz)

#### Model based
[MOReL: Model-Based Offline Reinforcement Learning](https://arxiv.org/pdf/2005.05951.pdf)

[MOPO: Model-based Offline Policy Optimization](https://arxiv.org/pdf/2005.13239.pdf)

[COMBO: Conservative Offline Model-Based Policy Optimization](https://arxiv.org/pdf/2102.08363.pdf)

[MODEL-BASED OFFLINE PLANNING](https://openreview.net/pdf?id=OMNB1G5xzd4) ICLR 2021, 8755

[NIPS 2020 Offline Workshop](https://offline-rl-neurips.github.io/papers.html)

[Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://arxiv.org/pdf/2006.03647.pdf) NIPS 2020

[Autoregressive Dynamics Models for Offline Policy Evaluation and Optimization](https://openreview.net/pdf?id=kmqjgSNXby), ICLR 2021

### app
[OPAL: OFFLINE PRIMITIVE DISCOVERY FOR ACCELERATING OFFLINE REINFORCEMENT LEARNING](https://arxiv.org/pdf/2010.13611.pdf), Offline + hrl

[Multi-task Batch Reinforcement Learning with Metric Learning](https://proceedings.neurips.cc//paper/2020/file/4496bf24afe7fab6f046bf4923da8de6-Paper.pdf), NIPS2020, Multi task, Generalize to unseen tasks.
[BATCH REINFORCEMENT LEARNING THROUGH CONTINUATION METHOD](https://openreview.net/pdf/84a7a35d996f84ab9fbbbcabccbdc21f44f2ba68.pdf), ICLR 2020, Offlien+continution.

[COG: Connecting New Skills to Past Experience with Offline Reinforcement Learning](https://arxiv.org/pdf/2010.14500.pdf), CoRL 2020.

[KEEP DOING WHAT WORKED: BEHAVIOR MODELLING PRIORS FOR OFFLINE REINFORCEMENT LEARNING](https://arxiv.org/pdf/2002.08396.pdf) ICLR 2020.

### datasets
[D4RL](https://arxiv.org/pdf/2004.07219.pdf)

### doc
[Offline Reinforcement Learning](https://github.com/hanjuku-kaso/awesome-offline-rl)

[NIPS2020 OfflineRL Workshop](https://offline-rl-neurips.github.io/papers.html)

[Video tutorial](https://www.youtube.com/watch?app=desktop&v=Es2G8FDl-Nc)

### code
[d4rl_evaluations](https://github.com/rail-berkeley/d4rl_evaluations), tensorflow

[AWAC, CQL, MOPO](https://github.com/hari-sikchi/offline_rl), pytorch

[polixir](https://github.com/polixir/OfflineRL), pytorch

## OPE
[Empirical Study of Off-Policy Policy Evaluation for Reinforcement Learning](https://arxiv.org/pdf/1911.06854.pdf),2019, survey of OPE.

[AUTOREGRESSIVE DYNAMICS MODELS FOR OFFLINE POLICY EVALUATION AND OPTIMIZATION](https://openreview.net/pdf?id=kmqjgSNXby), ICLR 2021.

[Doubly Robust Off-Policy Value and Gradient Estimation for Deterministic Policies](https://papers.nips.cc/paper/2020/file/75df63609809c7a2052fdffe5c00a84e-Paper.pdf), NIPS 2020.

[Double Reinforcement Learning for Efficient Off-Policy Evaluation in Markov Decision Processes](https://arxiv.org/pdf/1908.08526v3.pdf), [code](https://github.com/CausalML/DoubleReinforcementLearningMDP)

[AUTOREGRESSIVE DYNAMICS MODELS FOR OFFLINE POLICY EVALUATION AND OPTIMIZATION](https://openreview.net/pdf?id=kmqjgSNXby), ICLR 2021.

[Statistical Bootstrapping for Uncertainty Estimation in Off-Policy Evaluation](https://arxiv.org/pdf/2007.13609.pdf)[code](https://github.com/google-research/google-research/tree/master/policy_eval)

[Batch Policy Learning under Constraints](https://arxiv.org/pdf/1903.08738.pdf), FQE

[Doubly Robust Off-policy Value Evaluation for Reinforcement Learning](https://arxiv.org/pdf/1511.03722.pdf), Doubly-robust(DR)


### code
[DualDICE](https://github.com/google-research/google-research/tree/master/dual_dice),from google-research.

[github-code](https://github.com/theophilee/discrete-off-policy-evaluation),Implementation of importance sampling, direct, and hybrid methods for off-policy evaluation.

[code-Empirical Study of Off Policy Policy Estimation](https://github.com/clvoloshin/OPE-tools),OPE Tools

[BENCHMARKS FOR DEEP OFF-POLICY EVALUATION](https://arxiv.org/pdf/2103.16596.pdf), [[code]](https://github.com/google-research/deep_ope), ICLR 2021, This release provides: 1)Policies for the tasks in the D4RL, DeepMind Locomotion and Control Suite datasets (described below).
2) Policies trained with the following algorithms (D4PG, ABM, CRR, SAC, DAPG and BC) and snapshots along the training trajectory. This faciliates benchmarking offline model selection.[[auxiliary code]](https://github.com/google-research/google-research/tree/master/policy_eval), [[auxiliary code dice]](https://github.com/google-research/dice_rl)


## IRL
[GAIL- Generative Adversarial Imitation Learning](https://papers.nips.cc/paper/2016/file/cc7e2b878868cbae992d1fb743995d8f-Paper.pdf)

## Sim2Real
[Transfer from Simulation to Real World through Learning Deep Inverse Dynamics Model](https://arxiv.org/pdf/1610.03518.pdf), CoRR, 2016
propose a method to combine an inverse dynamics policy learned with expert demonstrations and a simulator policy trained in simulator.

[Offline Imitation Learning with a Misspecified Simulator](https://proceedings.neurips.cc/paper/2020/file/60cb558c40e4f18479664069d9642d5a-Paper.pdf), Nips, 2020

[Virtual-Taobao: Virtualizing Real-world Online Retail Environment for Reinforcement Learning](https://arxiv.org/pdf/1805.10000.pdf)

## IL
[Error Bounds of Imitating Policies and Environments](https://papers.nips.cc/paper/2020/file/b5c01503041b70d41d80e3dbe31bbd8c-Paper.pdf)
The paper analyzes the value gap between the expert policy and imitated policies by two imitation methods, behavioral cloning and generative adversarial imitation. The results support that generative adversarial imitation can reduce the compounding errors compared to behavioral cloning, and thus has a better sample complexity.

## RL-self-supervised
[SELF-SUPERVISED POLICY ADAPTATION DURING DEPLOYMENT](https://openreview.net/pdf?id=o_V-MjyyGV_)

## HRL
[Between MDPs and semi-MDPs:A framework for temporal abstractionin reinforcement learning](https://reader.elsevier.com/reader/sd/pii/S0004370299000521?token=6F22DD36E1D8394D262562BDA941EB802AF20CADF56CC8383CACBC8E83A27EFC1D7F8A5F169F49FE35CC8E50DEB3319E) Sutton, 1999, option framework

## ML
### Pareto

[Pareto Multi-Task Learning](https://arxiv.org/pdf/1912.12854.pdf)

[Multi-Objective Reinforcement Learning using Sets of Pareto Dominating Policies](https://jmlr.csail.mit.edu/papers/volume15/vanmoffaert14a/vanmoffaert14a.pdf), 2014, JMLR,Pareto in RL. 

[Bridging Theory and Algorithm for Domain Adaptation](https://arxiv.org/pdf/1904.05801.pdf), domain transfer??? MMD.

