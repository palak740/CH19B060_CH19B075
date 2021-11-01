# CH19B060_CH19B075

We derived below bayes classifiers assuming certain parameters to estimate class conaditional densities using maximum likelihood approach:
BayesA:- Assuming X|Y = −1 ∼ N(µ−,I) and X|Y = 1 ∼ N(µ+,I)
BayesB:- Assuming X|Y = −1 ∼ N(µ−, Σ) and X|Y = 1 ∼ N(µ+, Σ)
BayesC:- Assuminng X|Y = −1 ∼ N(µ−, Σ−) and X|Y = 1 ∼ N(µ+, Σ+)

we calculated prior probabilities and using bayes theorem under above mentioned assumptions we calulated posterior probabiliies and found the decision boundary using that.

we plotted decison boundary and concluded that:
BayesC classifier is best among all as it gives less error rate for both the datasets when compared to other two classifiers.
We get a linear decision boundary when both classes use same covariance matrix and a non linear decision boundary in case of BayesC classifier where covariance matrix is different for two classes.
BayesA and BayesB classifier gives almost similar result in ROC curve and decision boundary.

A non-parametric density estimation approach could have been used to solve this problem.
Pros:
Non-parametric denisty estimation, on the other hand, require fewer assumptions about the data, and consequently will prove better in situations where the true distribution is unknown or cannot be easily approximated using a probability distribution.

Cons:
We need more amount of data points to accurately estimate true density whereas in parametric relatively you require less.


