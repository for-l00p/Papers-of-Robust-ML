# Papers-of-Robust-ML
 Related papers for robust machine learning

## Contents 
- <a href="#General">General Defenses</a><br>
- <a href="#Detection">Adversarial Detection</a><br>
- <a href="#Verification">Verification</a><br>
- <a href="#Theoretical">Theoretical Analysis</a><br>

<a id='General'></a>
## General Defenses
* [A Spectral View of Adversarially Robust Features](http://papers.nips.cc/paper/8217-a-spectral-view-of-adversarially-robust-features.pdf) (NeurIPS 2018) <br/> Given the entire dataset X, use the eigenvectors of spectral graph as robust features. [[Appendix](http://papers.nips.cc/paper/8217-a-spectral-view-of-adversarially-robust-features-supplemental.zip)]

* [Deep Defense: Training DNNs with Improved Adversarial Robustness](http://papers.nips.cc/paper/7324-deep-defense-training-dnns-with-improved-adversarial-robustness.pdf) (NeurIPS 2018) <br/> They follow the linear assumption in DeepFool method. DeepDefense pushes decision boundary away from those correctly classified, and pull decision boundary closer to those misclassified.

<a id='Detection'></a>
## Adversarial Detection
* [A Simple Unified Framework for Detecting Out-of-Distribution Samples and Adversarial Attacks](http://papers.nips.cc/paper/7947-a-simple-unified-framework-for-detecting-out-of-distribution-samples-and-adversarial-attacks.pdf) (NeurIPS 2018) <br/> Fit a GDA on learned features, and use Mahalanobis distance as the detection metric.

* [Robust Detection of Adversarial Attacks by Modeling the Intrinsic Properties of Deep Neural Networks](http://papers.nips.cc/paper/8016-robust-detection-of-adversarial-attacks-by-modeling-the-intrinsic-properties-of-deep-neural-networks.pdf) (NeurIPS 2018) <br/> They fit a GMM on learned features, and use the probability as the detection metric.

<a id='Verification'></a>
## Verification
* [Provable Defenses against Adversarial Examples via the Convex Outer Adversarial Polytope](https://arxiv.org/pdf/1711.00851.pdf) (ICML 2018) <br/> By robust optimization (via a linear program), they can get a point-wise bound of robustness, where no adversarial example exists in the bound. Experiments are done on MNIST.

* [Scaling provable adversarial defenses](http://papers.nips.cc/paper/8060-scaling-provable-adversarial-defenses.pdf) (NeurIPS 2018) <br/> They add three tricks to improve the scalability of previously proposed method. Experiments are done on MNIST and CIFAR-10.

<a id='Theoretical'></a>
## Theoretical Analysis
* [Adversarial Vulnerability for Any Classifier](http://papers.nips.cc/paper/7394-adversarial-vulnerability-for-any-classifier.pdf) (NeurIPS 2018) <br/> Uniform upper bound of robustness for any classifier on the data sampled from smooth genertive models.
