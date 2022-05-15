# Machine Learning
A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E

# Supervised Learning
+ right answers given

continous value

regression

classification -discrete value

# Unsupervised Learning

- e.g. clustering algorithm
- used in social network analysis, market segmentation
- e.g. non-clustering (cocktail party algorithm)
- linear combination, find structure in chaotic data

# Model & Cost Function
### model
m - # of training examples
x = "input" variable(s)
y = "output" variable

(x^(i), y^(i)) - ith training example (1 indexed)

h - a "hypothesis" function that takes in x's and maps to y

univariate linear regression
```
h(x) = theta0 + theta1 * x
```
theta* are the "parameter" values of the function
select theta* such that the cost function is minimized

### cost
cost: J(theta0, theta1)

cost function / squared error function: 
```
cost(f) = sum( (f(x) - actual)^2 ) / 2m
```

+ The mean is halved as a convenience for the computation of the gradient descent, as the derivative term of the square function will cancel out the 1/2 term.
![[Pasted image 20220515174136.png]]

