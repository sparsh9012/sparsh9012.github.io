---
date: 2017-01-16
title: Recommendation Systems
categories:
  - account-settings
description: Keep your account secure
type: Document
---

A recommender system is an information filtering system that seeks to predicts the rating given by a user to an item. This predicted rating then used to recommend items to the user. The item for which the predicted rating is high will be recommended to the user. This recommender system is utilized in recommendation of a broad range of items. For instance, it can be used to recommend movies, products, videos, music, books, news, Facebook friends, clothes, Twitter pages, Android/ios apps, hotels, restaurants, routes etc. It is used by almost all of the major companies to enhance their business and to enrich user experience like YouTube for recommending videos, Amazon & Ebay for recommending products, Netflix for recommending Movies, Airbnb for recommending rooms and hotels, Facebook for recommending friends etc.

![images/Untitled.png](Theory/Untitled.png)

A [recommendation system](https://en.wikipedia.org/wiki/Recommender_system) seeks to understand the user preferences with the objective of recommending him or her items. These systems has become increasingly popular in recent years, in parallel with the growth of internet retailers like Amazon, Netflix or Spotify. Recommender systems are used in a variety of areas including movies, music, news, books, research articles, search queries, social tags, and products in general. In terms of business impact, according to a recent [study](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.895.3477&rep=rep1&type=pdf) from Wharton School, recommendation engines can cause a 25% lift in number of views and 35% lift in number of items purchased. So it is worth to understand these systems.

[Graphics](https://www.notion.so/Graphics-f8ce1c4c3ff6479bb96df0a19de5fb5e)

In general, recommendation lists are generated based on user preferences, item features, user-item past interactions and some other additional information such as temporal (e.g., sequence-aware recommender) and spatial (e.g., POI recommender) data. Recommendation models are mainly categorized into collaborative ltering, content-based recommender system and hybrid recommender system based on the types of input data.

![images/Untitled%201.png](Theory/Untitled%201.png)

Collaborative ****fitering makes recommendations by learning from user-item historical interactions, either explicit (e.g. user’s previous ratings) or implicit feedback (e.g. browsing history). Content-based recommendation is based primarily on comparisons across items’ and users’ auxiliary information. A diverse range of auxiliary information such as texts, images and videos can be taken into account. Hybrid ****model refers to recommender system that integrates two or more types of recommendation strategies.

![images/image_(11).png](Theory/image_(11).png)

Recommendation engines have been around for a while and there have been some key learnings to leverage: A user’s actions are the best indicator of user intent. Ratings and feedback tends to be very biased and lower volumes. Past actions and purchases drive new purchases and the overlap with other people’s purchases and actions is a fantastic predictor.

![images/Untitled%202.png](Theory/Untitled%202.png)

### Articles

- Executive guide to building recommendation system [Part 1](https://jameskle.com/writes/rec-sys-part-1) and [Part 2](https://jameskle.com/writes/rec-sys-part-2) ([static.pdf](https://knowledge-tree.quip.com/-/blob/HbEAAAEuHVf/sVSHQIxrhdHCQmkrhLBiXw?name=static.pdf))
- [How to build a recommender system](https://neoteric.eu/blog/how-to-build-a-recommender-system/)
- [How Can We ‘Design’ An Intelligent Recommendation Engine?](https://app.getpocket.com/read/2445915387)
- How to build recommendation system [simple](https://towardsdatascience.com/how-to-build-a-recommendation-engine-quick-and-simple-aec8c71a823e) and [advanced](https://towardsdatascience.com/advanced-use-cases-for-recommendation-engines-4a420b14ab4e)
- [Matrix Factorization](http://www.quuxlabs.com/blog/2010/09/matrix-factorization-a-simple-tutorial-and-implementation-in-python/)
- [Build a Recommendation Engine With Collaborative Filtering](https://app.getpocket.com/read/2640328447)
- [Comprehensive Guide to build a Recommendation Engine from scratch (in Python)](https://app.getpocket.com/read/2232421080)
- [Building Python Recommendation Systems that Work](https://blog.mirumee.com/building-python-recommendation-systems-that-work-8d8d218c1464)

---

### To be explored...

- [https://github.com/YuyangZhangFTD/awesome-RecSys-papers](https://github.com/YuyangZhangFTD/awesome-RecSys-papers)
- [https://github.com/MaurizioFD/RecSys2019_DeepLearning_Evaluation](https://github.com/MaurizioFD/RecSys2019_DeepLearning_Evaluation)
- [https://github.com/robi56/Deep-Learning-for-Recommendation-Systems](https://github.com/robi56/Deep-Learning-for-Recommendation-Systems)

---

### **Reference Slides**

- [Deep Learning in RecSys by Balázs Hidasi](http://pro.unibz.it/projects/schoolrecsys17/DeepLearning.pdf)
- [Lessons from Industry RecSys by Xavier Amatriain](http://pro.unibz.it/projects/schoolrecsys17/RecsysSummerSchool-XavierAmatriain.pdf)
- [Architecting Recommendation Systems by James Kirk](https://www.slideshare.net/JamesKirk58/boston-ml-architecting-recommender-systems)
- [Recommendation Systems Overview by Raimon and Basilico](http://nn4ir.com/ecir2018/slides/08_RecommenderSystems.pdf)

---

### **Benchmarks**

- [MovieLens Benchmarks for Traditional Setup](https://github.com/microsoft/recommenders/blob/master/benchmarks/movielens.ipynb)
- [Microsoft Tutorial on Recommendation System at KDD 2019](https://github.com/microsoft/recommenders)

---

### **Algorithms & Approaches**

- [Collaborative Filtering for Implicit Feedback Datasets](http://yifanhu.net/PUB/cf.pdf)
- [Bayesian Personalised Ranking for Implicit Data](https://arxiv.org/pdf/1205.2618)
- [Logistic Matrix Factorisation](https://web.stanford.edu/~rezab/nips2014workshop/submits/logmat.pdf)
- [Neural Network Matrix Factorisation](https://arxiv.org/abs/1511.06443)
- [Neural Collaborative Filtering](https://arxiv.org/abs/1708.05031)
- [Variational Autoencoders for Collaborative Filtering](https://arxiv.org/abs/1802.05814)

---

### **Evaluations**

- [Evaluating Recommendation Systems](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/EvaluationMetrics.TR_.pdf)

[Netflix at RecSys 2016 - Recap](https://netflixtechblog.com/netflix-at-recsys-2016-recap-e32d50d22ecb)

[](http://courses.ischool.berkeley.edu/i290-dm/s11/SECURE/a1-koren.pdf)

[Special Types](https://www.notion.so/c59b6d832f5240c2acb3acaa4487d14b)