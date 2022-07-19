# nn_from_scratch
A neural network built in numpy w/ ReLU/Sigmoid layers using SGD/Adam optimization to solve bit AND (&amp;).

**Activation Functions:** Leaky ReLU and Sigmoid available, I ended up using Leaky ReLU.

**Neural Net:** Built with structure 2 -> 10 -> 1 (one hidden layer). Evaluates with batches.

**Optimizers:** SGD and Adam. The implementation of Adam is different than the paper, but mathematically equivalent. Also I penalize large weights.

---------

**Results:**
```
0 AND 0 is -0.15923
0 AND 1 is -0.01149
1 AND 0 is -0.01174
1 AND 1 is 1.02833
```
