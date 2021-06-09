# Udacity Artificial Intelligence for Trading Nanodegree - Project: Sentiment Analysis with Neural Networks

- [Introduction](#introduction)
- [Getting started](#getting-started)
- [Dependencies](#dependencies)
- [Instructions](#instructions)
- [References](#references)
- [License](#license)

## Introduction

This project builds a deep learning model to classify the sentiment of messages from [StockTwits](https://stocktwits.com/), a social network for investors and traders. The model will be able to predict if any particular message is positive or negative. From this, it is possible to generate a signal of the public sentiment for various ticker symbols.

## Getting started

1. Fork this repository
2. Ensure you have all the dependencies
3. Follow the instructions below

## Dependencies

Install one of the following Python virtual environment managers:

- [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html), or
- [Virtualenv](https://virtualenv.pypa.io/), or
- [Pipenv](https://pipenv.pypa.io/)

The following instructions refer to Miniconda. Check out the respective links above in case you need help with any of the other methods.

## Instructions

Create a new `ai-trading-sentiment-analysis` Conda environment installing the required packages:

```bash
conda create --file ai-trading-sentiment-analysis.yml
```

Activate the environment:

```bash
conda activate ai-trading-sentiment-analysis
```

Start Jupyter:

```bash
jupyter notebook
```

Open the `sentiment_analysis.ipynb` notebook and follow the instructions.

## References

- [Pipenv vs virtualenv vs conda environment](https://medium.com/@krishnaregmi/pipenv-vs-virtualenv-vs-conda-environment-3dde3f6869ed)
- [Miniconda installation](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)
- [Conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
- [Jupyter Notebook Cheat Sheet](https://www.edureka.co/blog/wp-content/uploads/2018/10/Jupyter_Notebook_CheatSheet_Edureka.pdf)
- [Jupyter Lab Cheat Sheet](https://www.anaconda.com/wp-content/uploads/2019/03/11-2018-JupyterLab-Notebook-Cheatsheet.pdf)

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2021 © [Thomas Weibel](https://github.com/thom).
