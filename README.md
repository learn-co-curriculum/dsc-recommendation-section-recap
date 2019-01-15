
# Section Recap

## Introduction

This short lesson summarizes key takeaways from section 39

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

## Key Takeaways

The key takeaways from this section include:

* Recommendation approaches can consist of simply recommending popular items (without personalization), or using classification algorithms which takes into account past customer behavior
* When using algorithms, the two main types are content-based algorithms (recommending new content based on similar _content_), or collaborative filtering based (recommending new content based on similar types of _users_)
* Collaborative Filtering (CF) is currently the most widely used approach to build recommendation systems
* The key idea behind CF is that similar users have similar interest and that a user generally likes items that are similar
* CF is filling an "empty cell" (which is eg an unseen movie on netflix) in the utility matrix based on the similarity between users or item. Matrix Factorization or Decomposition can help us solve this problem.
* Matrix Decomposition can be reformulated as an optimization problem with loss functions and constraints
* Matrix Decomposition can be done using either Singular Value Decompisition (SVD) or Alternating Least Squares (ALS)
* Spark's ALS implementation can be be used to build a scalable and efficient reommendation system
