# Variational Inference Bayesian Neural Networks
## Uncertainties in deep learning
Modern deep learning models are typically unable to deal with uncertainties, for instance in classification or regression tasks.
These uncertainties can be estimated via Bayesian Deep Learning, resulting in powerful tools which are able to capture aleatoric and epistemic uncertainties:
* aleatoric uncertainties: noise inherent in the data, which cannot be reduced by increasing the dataset size;
* epistemic uncertainties: uncertainty in the model parameters, and therefore can be minimised given enough data.

## Method
The method presented was first developed in [arXiv:1703.04977](https://arxiv.org/pdf/1703.04977.pdf), and translated into a particle physics applications in [arXiv:2003.11099](https://arxiv.org/abs/2003.11099) and [arxiv:2104.04543](https://arxiv.org/pdf/2104.04543.pdf).
In order to capture epistemic uncertainty in a neural network we can place a prior over its parameters 

<img src="https://render.githubusercontent.com/render/math?math=\theta \sim \mathcal{N}(\mu, \sigma)">

## Notebooks

We provide a few example notebook to illustrate the technique.

