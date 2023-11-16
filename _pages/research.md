---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=vuP7r6cAAAAJ">Google Scholar</a>.



### Super ensemble learning with the Highly Adaptive Lasso

Complex and highly varying data models pose challenges on ensemble estimation and optimal asymptotic bias-variance trade-off for targets of inference. In this upcoming article, we propose a super learner using the Highly Adaptive Lasso (HAL). The proposed method is a flexible and powerful super learner converging at a guaranteed rate of $n^{-2/3}$ (up to log $n$-factor) in excess risks. By choosing the sectional variation norm large enough (undersmoothing), the target feature of this super learner is an asymptotically linear estimator for the target feature of the true function, possibly for an arbitrary target in a large class of smooth features. The asymptotic result relies on weaker conditions with reduced dimensions, which is applicable in longitudinal and mediation analysis with high-dimensional imaging data and health registry data. 

- [Preprint (upcoming)]().

### Higher order targeted maximum likelihood estimation

Asymptotic efficiency of targeted maximum likelihood estimation (TMLE) relies on a second order remainder being asymptotically negligible. However, in finite samples, the second order remainder can dominate the sampling distribution. By targeting a recursively defined set of data-adaptive, pathwise differentiable parameters, we propose a new higher order TMLE that relies on a higher order remainder being negligible. The new method makes no assumption on higher order pathwise differentiability and is practical for implementation. With HAL representation of tangent spaces, the algorithm can be fully computerized, requiring no analytical derivation of higher order canonical gradients. 

- [Preprint](https://arxiv.org/abs/2101.06290).
- Blog of [Young Statisticians Europe (YSE)](https://youngstats.github.io/post/2021/03/10/higher-order-targeted-maximum-likelihood-estimation/).

### Targeted learning for likelihood based longitudinal mediation

Causal mediation with survival and longitudinal data underscores the challenge of analyzing complex multivariate target parameters defined across multiple time points by different static and stochastic interventions, and is frequently complicated by censoring mechanisms and competing risks. In this paper, we propose a one-step targeted estimation approach that handles all the challenges above with a unified data likelihood estimation. This strategy intrinsically respects the model space by targeting multiple parameters with one maximum likelihood estimator. Utilizing HAL representation of the efficient influence curves further reduces computational costs and improves finite-sample performance, especially under near-violation of positivity assumptions. The proposed method is versatile for emulated trials and hypothetical interventions based on electronic health records (EHR).

- [Preprint](https://arxiv.org/abs/2304.04904).

### Reproducibility of neuroimaging data

Neuroimaging features complex high-dimensional data with no ground truth in measurement; therefore, data reproducibility remains a fundamental question for any machine learning studies with neuroimaging data. For fingerprinting statistics, we prove the limit distribution in permutation tests against the weaker null of exchangeability, and illustrate potential applications in aging and heritability research with Human Connectome Project (HCP) and Baltimore Longitudinal Study of Aging (BLSA) data. We propose a novel nonparametric reproducibility metric, discriminability; we show that optimizing discriminability improves performance in subsequent inferential tasks, regardless of what the actual task is, both theoretically and with the Consortium for Reliability and Reproducibility (CoRR) data. We show that discriminability is deterministically equivalent to classical intra-class correlation coefficients (ICC) when dealing with univariate data under parametric assumptions, while being robust under nonparametric and multivariate settings. The results provide a toolbox for refining imaging data preprocessing pipelines and experimental designs, and lays the foundation for the reliable clinical application of functional connectivity.

- Statistical analysis of data repeatability measures ([preprint](https://arxiv.org/abs/2005.11911)).
- Eliminating accidental deviations to minimize generalization error and maximize replicability: Applications in connectomics and genomics (published on [PLOS Computational Biology](https://doi.org/10.1371/journal.pcbi.1009279)).
- On statistical tests of functional connectome fingerprinting (published on [The Canadian Journal of Statistics](https://doi.org/10.1002/cjs.11591)). Also in [Stats & Data Science Views](https://www.statisticsviews.com/article/laymans-abstract-for-canadian-journal-of-statistics-paper-on-statistical-tests-of-functional-connectome-fingerprinting/). 

### Clinical trial on Primary Progressive Aphasia

Primary Progressive Aphasia (PPA) is a rare neurodegenerative disease that primarily affects language functions. In a clinical trial (Clinical Trial Identifier: [NCT02606422](https://clinicaltrials.gov/study/NCT02606422)), we report the benefitial effect of transcranial direct current stimulation (tDCS) therapy in combination with conventional speech-language intervention. We present the first supporting evidence that the functional connectivity changes between the stimulated area and other areas of the language network constructs a mechanism for tDCS effects in PPA. We identify areas whose volumes predict the additional tDCS effects on individuals. We discover rare generalization (near-transfer) effects to untrained tasks, specifically to behavioral tasks with potentially overlapped brain function such as semantic fluency. Future research aims to confirm and understand functional netowrk and other neural mediation mechanisms that explain the specificity of tDCS effects, as well as to design precision health algorithms that optimize individual benefits. 

- Specificity in generalization effects of transcranial direct current stimulation over the left inferior frontal gyrus in Primary Progressive Aphasia (published on [Neuromodulation: Technology at the Neural Interface](https://doi.org/10.1016/j.neurom.2022.09.004)). 
- Selective functional network changes following tDCS-augmented language treatment in Primary Progressive Aphasia (published on [Frontiers in Aging Neuroscience](https://doi.org/10.3389/fnagi.2021.681043)). 
- Reductions in GABA following a tDCS-language intervention for primary progressive aphasia (published on [Neurobiology of Aging](https://doi.org/10.1016/j.neurobiolaging.2019.03.011)). 
- Brain volumes as predictors of tDCS effects in primary progressive aphasia (published on [Brain and Language](https://doi.org/10.1016/j.bandl.2019.104707)). 
- The effect of tDCS on functional connectivity in primary progressive aphasia (published on [NeuroImage: Clinical](https://doi.org/10.1016/j.nicl.2019.101734)). 

