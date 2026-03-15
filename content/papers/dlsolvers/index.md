---
title: "Deep Learning Solutions of Large Non-Convex Life-Cycle Models"
date: 2026-02-27
lastmod: 2026-02-27
author: ["Jeppe Druedahl","Raphaël Huleux","Jacob Røpke"]
description: "We introduce a novel deep learning algorithm for solving large life-cycle models with both continuous and discrete choices."
summary: "We introduce a novel deep learning algorithm for solving large life-cycle models with both continuous and discrete choices. This allows us to simultaneously account for both labor supply choices with human capital accumulation, portfolio choices with a risky and a risk-free asset, and housing and mortgage choices. We work directly on the Bellman equation and approximate both value and policy functions with neural networks, and use a simulated training sample instead of tensor product grids. This substantially alleviates the curse of dimensionality. We demonstrate this in a consumption-saving model with multiple durable goods subject to non-convex adjustment costs where our deep learning algorithm clearly outperforms a standard value function iteration. We confirm that we can accurately solve a large life-cycle model in 12 hours on a single GPU. We solve the model simultaneously across all periods instead of with backward induction. This simplifies transfer learning, where a new solution for a new set of parameters in a calibration or estimation can easily be achieved. An accompanying easy-to-use software package implements the method."

---

##### Abstract

We introduce a novel deep learning algorithm for solving large life-cycle models with both continuous and discrete choices. This allows us to simultaneously account for both labor supply choices with human capital accumulation, portfolio choices with a risky and a risk-free asset, and housing and mortgage choices. We work directly on the Bellman equation and approximate both value and policy functions with neural networks, and use a simulated training sample instead of tensor product grids. This substantially alleviates the curse of dimensionality. We demonstrate this in a consumption-saving model with multiple durable goods subject to non-convex adjustment costs where our deep learning algorithm clearly outperforms a standard value function iteration. We confirm that we can accurately solve a large life-cycle model in 12 hours on a single GPU. We solve the model simultaneously across all periods instead of with backward induction. This simplifies transfer learning, where a new solution for a new set of parameters in a calibration or estimation can easily be achieved. An accompanying easy-to-use software package implements the method.

---

+ [Paper](dlsolvers.pdf)

---

##### Citation


```BibTeX
@techreport{DruedahlHuleuxRopke2026,
author = {Jeppe Druedahl and Raphaël Huleux and Jacob Røpke},
year = {2026},
title = {Deep Learning Solutions of Large Non-Convex Life-Cycle Models}}
```
