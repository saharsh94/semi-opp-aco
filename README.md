ReadMe

Semi-Supervised Approach with OBL and RL in ACO

This repository implements a semi-supervised approach to evaluate the performance of Opposition-Based Learning (OBL) and Reinforcement Learning (RL) in an Ant Colony Optimization (ACO) algorithm. The method is tested on multi-label datasets, with experiments conducted using 20% and 40% of labeled data to compare the results.

The code is provided as a Jupyter Notebook (.ipynb), and the datasets used in the experiments are available in the dataset folder. Please note that the associated paper describing this work is currently under review and has not yet been published.

Contributions and feedback are encouraged to help refine this approach.
***************************************************************************************

Abstract
This paper introduces a novel feature selection method for multi-label data, using Ant Colony Optimization (ACO) enhanced with Temporal Difference (TD) reinforcement learning, opposition-based learning (OBL), and semi-supervised learning. The key innovation lies in the application of semi-supervised learning, where we explore the impact of different proportions of labeled data—specifically 20% and 40%—on the algorithm's performance. This marks the first time such a model has been applied to multi-label datasets. In our approach, ACO is used to navigate the feature space, while TD learning dynamically updates heuristic functions, specifically the state value V, to better predict future rewards for selected feature subsets. OBL further enhances the exploration process by considering both original and opposite solutions, ensuring a more comprehensive search. The semi-supervised learning aspect of our method is particularly critical, as it allows the algorithm to leverage the structure of the unlabeled data, improving the quality of feature selection even when labeled data is scarce. We evaluated our methods on nine diverse multi-label datasets using the Multi-Label K-Nearest Neighbors (MLKNN) classifier, measuring performance with accuracy and Hamming loss metrics. The results demonstrate that our hybrid approach, which uniquely combines ACO, TD learning, OBL, and semi-supervised learning, significantly outperforms traditional feature selection techniques. The experiments with 20% and 40% labeled data highlight the effectiveness of the semi-supervised approach in enhancing classification performance and identifying more relevant feature subsets, establishing a new benchmark for multi-label feature selection.
