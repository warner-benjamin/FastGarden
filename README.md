# FastGarden

My FastGarden submissions, fast.ai forum competition: https://forums.fast.ai/t/fastgarden-a-new-imagenette-like-competition-just-for-fun

# Submissions

Current best submission: 

* **80.41% +-0.73%**
  * Experiment 7.3 in FastGarden MK-ResNeXt-50.ipynb
  * Using MK-SE-ResNeXt-50E, which adds [MDConvs](https://arxiv.org/abs/1907.09595/) to fast.ai’s XSE-ResNeXt. See the notebook for more details.
  * Ranger optimizer, Label Smoothing Cross Entropy loss, fit_flat_cos with learning rate of 8e-3.

Prior best submission:

* **76.55% +- 0.25%**
  * Second submission in FastGarden XSE-ResNeXt-50.ipynb
  * XSE-ResNeXt50 with a (24,32,64) stem and GeM pool
  * Ranger optimizer, Label Smoothing Cross Entropy loss, fit_flat_cos with learning rate of 8e-3.

