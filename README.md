# Transnet
## Model implementation
Code implementation: https://github.com/jaejunchoe/HAIDS-Lab/tree/main/Transnet


## What is the Transnet Model?
![슬라이드7](https://github.com/user-attachments/assets/9a41347d-6d0d-46b7-9faf-3bb26967f780)


## The Reason for the Emergence of TransNet
![슬라이드6](https://github.com/user-attachments/assets/7bcb1e67-61bc-4583-810d-706a8914c58d)
DeepCoNN had a prerequisite that both user and item reviews must exist simultaneously. However, this condition is not practically suitable for recommendation systems. This is because recommendation systems need to predict ratings even in situations where there are no reviews available for a particular user or item. **Therefore, to address this conditional limitation of DeepCoNN, the structure was redesigned to enable inference even in the absence of reviews.**


## The basic structure of the Transnet model.
![슬라이드9](https://github.com/user-attachments/assets/483f66fd-4935-4583-907f-8aeb1e8903c6)

`* Reference:` Catherine, Rose, and William Cohen. "Transnets: Learning to transform for recommendation." Proceedings of the eleventh ACM conference on recommender systems. 2017.

## Citation (Paper And Publicly Available Code)
1. Catherine, Rose, and William Cohen. "Transnets: Learning to transform for recommendation." Proceedings of the eleventh ACM conference on recommender systems. 2017.

2. Publicly Available Code
   <br/>URL: https://github.com/winterant/TransNets


## Dataset
* Amazon Reviews'23 - Subscription_Boxes Dataset 

URL: https://amazon-reviews-2023.github.io/
