Overview
----
This repository is an implementation of the paper "Improving Adversarial Robustness via Probabilistically Compact Loss with Logit Constraints".

Introduction
----
In this paper, we point out a unique insight from the predictive behavior of adversarial samples that they tends to be misclassified into the most probable false classes. This inspires us to propose a new Probabilistically Compact (PC) loss with logit constraints which is a drop-in replacement for cross-entropy (CE) loss to increase model adversarial robustness. Specifically, PC loss enlarges the probability gaps between true class and false classes meanwhile the logit constraints prevent the gaps from being melted by a small perturbation.

Predictive behavior of adversarial samples
----
<p><img src="Figures/Motivation.PNG" alt="test" width="800"></p>

Demo of Training effect
----
<p><img src="Figures/Effect.PNG" alt="test" width="400"></p>

Results
----
<p><img src="Figures/MNIST.PNG" alt="test" width="800"></p>

Model Training and Evaluation
----

Dependencies
-----
* Python 3.7
* Pytorch 1.3
