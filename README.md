# Recommendation System Experiment Notes
### 💪 Motivation
A recommendation system is a type of machine learning system that filters through a large amount of information and recommends those that are most relevant to a particular user. It is a tool that helps users discover new products, services, content, or people based on their past behavior and preferences. Recommendation systems are widely used in many different industries, including e-commerce, streaming services, social media, and music.<br />
<br />
This guide will walk you through the process of building a recommender system from scratch, using the TMDB 5000 Movie Dataset as experimental data.
### 🎯 Goal
The goal is to create a system that can rival the performance of Xiaohongshu's recommendation engine.
### 🖌️ Steps for a Recommendation System
![alt text](https://github.com/helgesander02/recommendationsystem_study/blob/main/docs/process.jpg)

## Experimental Steps for the TMDB 5000 Movie Dataset
https://miro.com/welcomeonboard/QnhWelFoMmNqNEFHaDZEZW92NmxKRDZQR095cmlzVTduYUhObjdFNzZWR0V1OHkwYmV5OEVRZERsMU1XUFpXT3wzNDU4NzY0NTc0MzMzMTc0Mjg2fDI=?share_link_id=253987407001

## Dataset
[TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) <br />

## Reference
### Recommendation System Description
* [RecommenderSystem (Chinese)](https://github.com/wangshusen/RecommenderSystem)
* [AI-RecommenderSystem (Chinese)](https://github.com/zhongqiangwu960812/AI-RecommenderSystem)
* [Twitter's Recommendation Algorithm](https://github.com/twitter/the-algorithm)
* [List of Recommender Systems](https://github.com/grahamjenson/list_of_recommender_systems?tab=readme-ov-file#open-source-recommender-systems)

### AB testing
* [Overlapping Experiment Infrastructure:More, Better, Faster Experimentation](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36500.pdf)

### Recall
* ItemCF: [Item-Based Collaborative Filtering Recommendation Algorithms](https://www.ra.ethz.ch/cdstore/www10/papers/pdf/p519.pdf)
* Swing: [Large Scale Product Graph Construction for Recommendation in E-commerce](https://arxiv.org/pdf/2010.05525)
* UserCF: [User-based Collaborative Filtering Algorithm Design and Implementation](https://iopscience.iop.org/article/10.1088/1742-6596/1757/1/012168/pdf)
* UserCF: [UTEG](https://github.com/twitter/the-algorithm/blob/main/src/scala/com/twitter/recos/user_tweet_entity_graph/README.md)
* Matrix Completion: [Privileged Matrix Factorization for Collaborative Filtering](https://www.ijcai.org/Proceedings/2017/0223.pdf)
* Matrix Completion: [Matrix completion by deep matrix factorization](https://www.sciencedirect.com/science/article/abs/pii/S0893608017302502)
* Approximate Nearest Neighbor Search: [Faiss](https://github.com/facebookresearch/faiss)
* 2-Tower: [Two Tower Model Architecture: Current State and Promising Extensions](https://blog.reachsumit.com/posts/2023/03/two-tower-model/)
* 2-Tower Pointwise: 
* 2-Tower Pairwise: [Embedding-based Retrieval in Facebook Search](https://arxiv.org/pdf/2006.11632)
* 2-Tower Listwise: [Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/6c8a86c981a62b0126a11896b7f6ae0dae4c3566.pdf)
* Deep Retrieval: [Deep Retrieval: Learning A Retrievable Structure for Large-Scale Recommendations](https://arxiv.org/pdf/2007.07203)
* TDM: [Learning Tree-based Deep Model for Recommender Systems](https://arxiv.org/pdf/1801.02294)
* JTM: [Joint Optimization of Tree-based Index and Deep Model for Recommender Systems](https://arxiv.org/pdf/1902.07565)
* OTM: [Learning Optimal Tree Models under Beam Search](https://arxiv.org/pdf/2006.15408)


### Light Ranker

### Heavy Ranker

### Re-ranking

### Mix-ranking