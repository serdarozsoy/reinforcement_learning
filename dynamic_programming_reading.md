## Dynamic Programming (DP) and Reinforcement Learning (RL) – Reading Assignment

Many reinforcement learning (RL) algorithms utilize dynamic programming methods. Dynamic Programming methods have been researched for years to solve MDPs (Markov Decision Processes) assuming that the agent has prefect knowledge of functions that define an environment. In machine learning, the environment is usually formulated as an MDP. The main difference between the classical dynamic programming methods and RL algorithms is that RL algorithms do not assume knowledge of an exact mathematical model of the MDP. RL algorithms target large MDPs where exact methods are not possible. RL problems such as Q-learning fits a problem setting under Markov decision processes because the environment is observable and an agent can iteratively and progressively learn to improve. Agent works towards obtaining optimal discounted reward from the environment.

Foundational material for DP in RL with examples.

https://github.com/dennybritz/reinforcement-learning/tree/master/DP/

### Additional Reads

1) Good Beginner/Midlevel Summary
- https://towardsdatascience.com/reinforcement-learning-demystified-solving-mdpswith-dynamic-programming-b52c8093c919
2) Comprehensive Reading:
- http://incompleteideas.net/book/bookdraft2018jan1.pdf
- http://www.wildml.com/2016/10/learning-reinforcement-learning/
3) Midlevel/Advanced Summary:
- https://www.cs.cmu.edu/~katef/DeepRLControlCourse/lectures/lecture3_mdp_planning.pdf
4) Advanced
- https://djrusso.github.io/RLCourse/index
