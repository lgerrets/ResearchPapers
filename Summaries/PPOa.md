# Proximal Policy Optimization Algorithms

[arXiv](https://arxiv.org/abs/1707.06347)

[codes](https://github.com/openai/baselines/tree/master/baselines/ppo2) [codes2](https://github.com/berkeleydeeprlcourse/homework/tree/master/hw4)

## TLDR

PPO is a simple to implement yet general agorithm for RL, that compares favorably against previous state-of-the-art algorithms on both continuous control tasks and Atari environments.

## Aim

They consider that the 3 state-of-the-art approaches Trust Region Policy Optimization [Sch+15b], policy gradient [Mni+16], and Q-learning [Mni+15] each have their disadvantages. They aim at proposing their Proximal Policy Gradient algorithm that performs as well or better than previous algorithms (A2C, ACER, PG, TRPO, CEM), while being simple to implement, and requiring no hyperparameterizing that depends on the environment. They also compare different hyperparameterizations.

## Methods

<whats new in their approaches>

Similarly to previous actor critic algorithms, PPO simultaneously optimizes the Value function and the policy in a single loss function. In PPO, they modified the term that optimizes the policy to negate 


## Technical details

<mathematical notations, proofs>

<setups>

<parameterizing>

## Experiments - results

<comparable experiments on typical dataset/environments...>

<breakthroughs>

## My thoughts and takeaways

<pros>

<cons>

<related stuff>

## References

[Mni+15] V. Mnih, K. Kavukcuoglu, D. Silver, A. A. Rusu, J. Veness, M. G. Bellemare, A. Graves,
M. Riedmiller, A. K. Fidjeland, G. Ostrovski, et al. “Human-level control through deep
reinforcement learning”. In: Nature 518.7540 (2015), pp. 529–533.

[Mni+16] V. Mnih, A. P. Badia, M. Mirza, A. Graves, T. P. Lillicrap, T. Harley, D. Silver, and
K. Kavukcuoglu. “Asynchronous methods for deep reinforcement learning”. In: arXiv
preprint arXiv:1602.01783 (2016).

[Sch+15a] J. Schulman, P. Moritz, S. Levine, M. Jordan, and P. Abbeel. “High-dimensional contin-
uous control using generalized advantage estimation”. In: arXiv preprint arXiv:1506.02438
(2015).

[Sch+15b] J. Schulman, S. Levine, P. Moritz, M. I. Jordan, and P. Abbeel. “Trust region policy
optimization”. In: CoRR, abs/1502.05477 (2015).

## Top Figures

<![Figure N](../Ressources/Abc/FigN.png "")>

## Metadata

```
@article{DBLP:journals/corr/SchulmanWDRK17,
  author    = {John Schulman and
               Filip Wolski and
               Prafulla Dhariwal and
               Alec Radford and
               Oleg Klimov},
  title     = {Proximal Policy Optimization Algorithms},
  journal   = {CoRR},
  volume    = {abs/1707.06347},
  year      = {2017},
  url       = {http://arxiv.org/abs/1707.06347},
  archivePrefix = {arXiv},
  eprint    = {1707.06347},
  timestamp = {Mon, 13 Aug 2018 16:47:34 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/SchulmanWDRK17},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

Tags:

