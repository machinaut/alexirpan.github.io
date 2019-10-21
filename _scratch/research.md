---
layout: page
title: Research
permalink: /research/
---

*Last updated September 25, 2017.*

My current research interests are transfer learning and deep reinforcement
learning, with a bias towards their applications to robotics.

This page is divided into post-undergrad projects and undergrad projects.
Post-undergrad projects are significantly lower quality, but I leave them up
because I'm still slightly proud of what I accomplished, given what I knew
at the time.

Project list:

- Clobbered for auto generated table of contents
{:toc}


---------------------------------------------

<p></p>

# Post-Undergrad Work

### Using Simulation and Domain Adaptation to Improve Efficiency of Deep Robotic Grasping

*Konstantinos Bousmalis\*, Alex Irpan\*, Paul Wohlhart\*, Yunfei Bai, Matthew Kelcey, Mrinal Kalakrishnan, Laura Downs, Julian Ibarz, Peter Pastor, Kurt Konolige, Sergey Levine, Vincent Vanhoucke. Asterisk indicates equal contribution.*

Paper and Video: [here](https://sites.google.com/view/graspgan)

Combines several domain adaptation techniques (both feature-level and pixel-level) to learn real-world grasping policies from monocular RGB images.


### Learning Hierarchical Information Flow with Recurrent Neural Modules

*Danijar Hafner, Alex Irpan, James Davidson, Nicolas Heess*

Paper: [here](https://arxiv.org/abs/1706.05744)

Proposes ThalNet, a network architecture inspired by the thalamus in the brain. Accepted to NIPS 2017.

---------------------------------------------

<p></p>

# Undergrad Work

### Exploring Boosted Neural Nets for Rubik's Cube Solving

*Alex Irpan*

*Spring 2016. Final project for CS 281B, Advanced Topics in Decision Making*

Poster (click for full size):

[![Poster](/public/research/posterimage.png)](/public/research/poster.pdf)

Paper: [here](/public/research/nips_2016.pdf)

Code: [GitHub](https://github.com/alexirpan/rubik_research)

Applies AdaBoost to a online data stream to aid in training a neural net to
classify the next move in a Rubik's Cube solution.


### Factored Q-Learning in Continuous State-Action Spaces

*Alex Irpan, mentored by John Schulman*

*Fall 2015. Final project for CS 281A, Statistical Learning Theory*

Poster (click for full size):

[![281A Poster](/public/research/281aposterimage.png)](/public/research/281aposter.pdf)

Informal Writeup: [PDF](/public/research/281areport.pdf)

Code: [BitBucket](https://bitbucket.org/airpan/fall15-research)

Represents a Q-function as the sum of one Q-function for each dimension of the
action space, aiming to avoid the curse of dimensionality in high-dimensional
discretized MDPs.


### An Overview of Sublinear Machine Learning Algorithms

*Alex Irpan\*, Ronald Kwan\* (worked equally)*

*Spring 2015. Final project for CS 270, Combinatorial Algorithms and Data Structures*

Report: [PDF](/public/research/sublinear-algorithms-optimization.pdf)

A survey paper summarizing algorithms used to solve SDPs and learn SVMs in sublinear
time.


### Integrating Monte Carlo Tree Search with Reinforcement Learning

*Alex Irpan, mentored by John Schulman*

*Fall 2014 - Spring 2015*

Code: [BitBucket](https://bitbucket.org/airpan/research-code)

Regresses policy $$\pi$$ to target values generated by MCTS, with $$\pi$$
as the rollout policy. Note: done before AlphaGo was announced.