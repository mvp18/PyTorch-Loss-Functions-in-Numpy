Some code snippets I frequently refer to for ensuring correct usage of PyTorch loss functions. Have found the [official documentation](https://pytorch.org/docs/1.5.1/nn.html#loss-functions) to be lacking sufficient 
clarity at times and also proper examples, so wrote some numpy code for understanding purposes.


The two notebooks have the following implementations:

#### Regression Based Losses.ipynb

- L1Loss
- L2/MSE Loss
- SmoothL1Loss

#### Classification Based Losses.ipynb

- CrossEntropyLoss
- NLLLoss
- PoissonNLLLoss
- KLDivLoss
- BCELoss
- BCEWithLogitsLoss
- MultiLabelMarginLoss
- MarginRankingLoss
- HingeEmbeddingLoss
- MultiLabelSoftMarginLoss
- SoftMarginLoss
- CosineEmbeddingLoss
- MultiMarginLoss
- TripletMarginLoss

### References

[1] https://pytorch.org/docs/1.5.1/nn.html#loss-functions

### Contributing

If you find any errors or have any questions, kindly raise an issue.
