
# This is a record of current experiment result on some realistic noisy label datasets

## 1. Clothing1M dataset
from: [CVPR-15: Learning from Massive Noisy Labeled Data for Image Classification](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Xiao_Learning_From_Massive_2015_CVPR_paper.pdf)
 + 14 classes: T-shirt, Shirt, Knitwear, Chiffon, Sweater, Hoodie, Windbreaker, Jacket, Down Coat, Suit, Shawl, Dress, Vest, and Underwear
 + noisy labeled training dataset ($D_\eta$): $10^6$
 + clean train data($D_c$): 47,570
 + clean validation set: 14,313
 + clean test set: 10,526
 
 ![Noise confusion matrix](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Clothing1Mnoise_transition_matrix.png) 
 
 
#### 1. [CVPR-15: Learning from Massive Noisy Labeled Data for Image Classification]()
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Clothing1MResult.png)


#### 2. [CVPR-17: Making Deep Neural Networks Robust to Label Noise: A Loss Correction Approach](https://arxiv.org/pdf/1609.03683.pdf)
![some resutl](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/cvpr17_result.PNG)

#### 3. [CVPR-18: Joint Optimization Framework for Learning With Noisy Labels](https://arxiv.org/pdf/1803.11364v1.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/cvpr18_result.PNG)

#### 4. [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise](https://arxiv.org/pdf/1711.07131.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/clean_net.PNG)
#### 5. [ECCV-18: CurriculumNet: Weakly Supervised Learning from Large scale Web Images]()

#### 6. [ECCV-18: Deep Bilevel Learning](http://openaccess.thecvf.com/content_ECCV_2018/papers/Simon_Jenni_Deep_Bilevel_Learning_ECCV_2018_paper.pdf)
69.9(only use noisy training data) -> 79.9(fine-tuning)

#### 6. [NIPS-18: Masking: A new perspective of noisy supervision](https://arxiv.org/pdf/1805.08193.pdf)

![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Masking-Clothing1M.PNG)

#### 7. [AAAI-19: Safeguarded Dynamic Label Regression for Noisy Supervision(journal verison)](https://arxiv.org/abs/1903.02152?context=cs.CV)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/LCNN.PNG)

#### 8. [CVPR-19：Probabilistic End-to-End Noise Correction for Learning with Noisy Labels](https://arxiv.org/pdf/1903.07788.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/pencil2.PNG)

#### 9. [CVPR-19: Learning to Learn from Noisy Labeled Data](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Learning_to_Learn_From_Noisy_Labeled_Data_CVPR_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Learning2Learn.PNG)

#### 10. [CVPR-19: Weakly Supervised Image Classification through Noise Regularization](http://openaccess.thecvf.com/content_CVPR_2019/papers/Hu_Weakly_Supervised_Image_Classification_Through_Noise_Regularization_CVPR_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/weakly-supervised-Clothing1M.PNG)

#### 10. [CVPR-19: MetaCleaner: Learning to Hallucinate Clean Representations for Noisy-Labeled Visual Recognition](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_MetaCleaner_Learning_to_Hallucinate_Clean_Representations_for_Noisy-Labeled_Visual_Recognition_CVPR_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/MetaCleaner.PNG)

#### 11. [ICML-19: Unsupervised Label Noise Modeling and Loss Correction](https://arxiv.org/pdf/1904.11238v2.pdf)
about 71%
#### 10. [NIPS-19: L_DMI: A Novel Information-theoretic Loss Function for Training Deep Nets Robust to Label Noise](https://arxiv.org/pdf/1909.03388.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/DMI.PNG)
#### 11. [NIPS-19: Are Anchor Points Really Indispensable in Label-Noise Learning?]()
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/anchor-Clothing1M.PNG)

#### 10. [Meta-Weight-Net: Learning an Explicit Mapping For Sample Weighting](https://papers.nips.cc/paper/8467-meta-weight-net-learning-an-explicit-mapping-for-sample-weighting.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Meta-weight-Net-Clothing1M.PNG)


#### 15. [ICCV-19: Deep Self-Learning From Noisy Labels ](http://openaccess.thecvf.com/content_ICCV_2019/papers/Han_Deep_Self-Learning_From_Noisy_Labels_ICCV_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Deep-self-Clothing1M.PNG)

#### 16. [ICCV-19: Symmetric Cross Entropy for Robust Learning with Noisy Labels](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Symmetric_Cross_Entropy_for_Robust_Learning_With_Noisy_Labels_ICCV_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Symmetric-CE-Clothing1M.PNG)
#### 17. [ICCV-19: O2U-Net: A Simple Noisy Label Detection Approach for Deep Neural Networks](http://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_O2U-Net_A_Simple_Noisy_Label_Detection_Approach_for_Deep_Neural_ICCV_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/O2U-Net-Clothing1M.PNG)

#### 18. [Arixv-19: Improving MAE’s Fitting Ability while Preserving Its Noise-robustness](https://arxiv.org/pdf/1903.12141.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/IMAE.PNG)

#### 19. [ICLR-20: underview: DivideMiX: Learning with noisy labels as semi-supervised learning]




## 2. [WebVison dataset](http://www.vision.ee.ethz.ch/webvision/index.html)
from: [Arxiv17: Webvision database: Visual learning and understanding from web data](https://arxiv.org/pdf/1708.02862.pdf)
+ 1,000 classes: concepts in ImageNet ILSVRC12
+ noise rate: 20-40%

#### 1. [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise]()
#### 2. [ECCV-18: CurriculumNet: Weakly Supervised Learning from Large scale Web Images]()
#### 3. [ICML-18: MentorNet: Learning Data-Driven Curriculum for Very Deep Neural Networks on Corrupted Labels](http://proceedings.mlr.press/v80/jiang18c/jiang18c.pdf)
use all data or only use the first 50 classes of Google image subset
#### 4. [AAAI-19: Safeguarded Dynamic Label Regression for Noisy Supervision]()

#### 5. [ICML-19:	Understanding and Utilizing Deep Neural Networks Trained with Noisy Labels]()
only use the first 50 classes of Google image subset
#### 6. [NIPS-19: Combinatorial Inference against Label Noise]()
only use the randomly selected 100 classes

#### 7. [ICLR-20 underreview: IEG: Robust neural networks training to tackel severe label noise]()

#### 8. [ICLR-20: underview: DivideMiX: Learning with noisy labels as semi-supervised learning]()



## 3. [Food101-N](https://kuanghuei.github.io/Food-101N/)
from: [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise]()
+ 101 food classes 
+ 310k image, 55k verification, 
+ noise rate: 20%

#### 1. [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise]()
#### 2. [ECCV-18: CurriculumNet: Weakly Supervised Learning from Large scale Web Images]()
      not use Food101N created by cleanNet paper, but use Food101 and inject 20% noise

#### 3. [CVPR-19: MetaCleaner: Learning to Hallucinate Clean Representations for Noisy-Labeled Visual Recognition](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_MetaCleaner_Learning_to_Hallucinate_Clean_Representations_for_Noisy-Labeled_Visual_Recognition_CVPR_2019_paper.pdf)
#### 4. [ICCV-19: Deep self-Learning from Noisy Labels]()
#### 5. [ICLR-20: underview: Prestopping: How does Early stopping help generalization against label noise]()






## 4. [ANIMAL10N](https://dm.kaist.ac.kr/datasets/animal10n)
from: [ICML-19: SELFIE: Refurbishing Unclean Samples for Robust Deep Learning]()
#### 1. [ICML-19: SELFIE: Refurbishing Unclean Samples for Robust Deep Learning]()
#### 2. [ICLR-2020: Prestopping: How Does Early Stopping Help Generalization Against Label Noise?]()

