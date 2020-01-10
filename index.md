---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: page
---

<h1>Stratification Learning</h1>

## What is Stratification Learning?

_Stratification learning (SL)_ is a new machine learning paradigm developed in [RIKEN AIP-FUJITSU Collaboration Center (RAFCC)](https://aip.riken.jp/labs/lab-fujitsu/), a leading research institute of artificial intelligence in Japan.

### Beyond manifold learning

Stratification learning extends the concept of manifold learning for better handling of geometrically structured data in high dimensional spaces.
Manifold learning relies on the assumption that high dimensional data in real-world applications is often sparse and distributed along with a low dimensional manifold.
Stratification learning assumes that data are distributed along with a _stratified space_, which is a composite of manifolds of varying dimensions.
Moreover, such data are stratified according to _strata_, i.e., component manifolds of the stratified space.
By utilizing such a geometric structure, we can achieve an unprecedentedly efficient learning!


## Where do stratified spaces arise?
Data distributed around a stratified space appear in the following examples.
The applicability of SL is not limited to those; there would be many applications waiting to be discoverd!

### Multiobjective optimization
Under some mild conditions, the Pareto critical set and local Pareto set of generic multiobjective optimization problems admin a stratification.
Numerical optimizers give a sample from these solution sets.
Such a sample is a good leaning source of stratification learning.

### Biologcal data modeling
A stratified space also arises in modeling the genetypic divergence of a species in evolutionary biology.
It is known that genotypes of a species distribute along with a "curved" simplex.
A simplex is the simplest instance of stratified spaces, whose strata are vertices, edges, faces, and so on.
By using a simplicial model, we can efficiently represent such a biological phenomenon.


## Methods of Stratification Learning

### Bezier simplex
The Bezier simplex is a high dimensional version of the Bezier curve.
Since any stratified space is triangulable, the Bezier simplex is a primitive object to build up a complex stratified object.


## Refereed Papers
The following list provides published papers of SL and source code for reproducing experiments therein. 

1. Ken Kobayashi, Naoki Hamada, Akiyoshi Sannai, Akinori Tanaka, Kenich Bannai and Masashi Sugiyama: "Bézier Simplex Fitting: Describing Pareto Fronts of Simplicial Problems with Small Samples in Multi-Objective Optimization," in Proceedings of the 33rd AAAI Conference on Artificial Intelligence (AAAI-19), 2304-2313 (2019).
    - [paper](https://doi.org/10.1609/aaai.v33i01.33012304)
    - [code](https://github.com/rafcc/aaai-19.2786)
    - [supplements](https://arxiv.org/abs/1812.05222)
1. Akinori Tanaka, Akiyoshi Sannai, Ken Kobayashi and Naoki Hamada: "Asymptotic Risk of Bézier Simplex Fitting," in Proceedings of the 34th AAAI Conference on Artificial Intelligence (AAAI-20), in press.
    - [code](https://github.com/rafcc/aaai-20.1534)
    - [arxiv](https://arxiv.org/abs/1906.06924)

## Tools
- under preparation...
