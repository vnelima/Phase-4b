# Recommendation Systems - Recap

## Key Takeaways

The key takeaways from this section include:

* Recommendation approaches can consist of simply recommending popular items (without personalization), or using algorithms which takes into account past customer behavior
* When using algorithms, the two main types are content-based algorithms (recommending new content based on similar *content*), or collaborative filtering based (recommending new content based on similar types of *users*)
* Collaborative Filtering (CF) is currently the most widely used approach to build recommendation systems
* The key idea behind CF is that similar users have similar interests and that a user generally likes items that are similar to other items they like
* CF is filling an "empty cell" in the utility matrix based on the similarity between users or item. Matrix factorization or decomposition can help us solve this problem by determining what the overall "topics" are when a matrix is factored
* Matrix decomposition can be reformulated as an optimization problem with loss functions and constraints
* Matrix decomposition can be done using either Singular Value Decomposition (SVD) or Alternating Least Squares (ALS)
* The `surprise` library allows you to build models for CF
