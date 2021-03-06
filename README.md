# Prediction on Twitter COVID

This project is aimed to make daily prediction on people's overall attitude towards COVID-19 based on the epidemic data.

This project use pyspark as the fundamental to enable large scale prediction on distributed cluster.

It can be deployed on hadoop cluster or only a python environment.


## Datasets

Thanks a lot to these datasets.

[Covid Act Now](https://apidocs.covidactnow.org/)

[COVID-19 Twitter Dataset with Latent Topics, Sentiments and Emotions Attributes
](https://www.openicpsr.org/openicpsr/project/120321/version/V11/view;jsessionid=A13FBEE2E74D53DDB6E973A5A1CF69EF)

## Main Work

I utilize some covid data as features to train a model on predicting sentiment data.

![sentiment data](./pics/sentiment_dataset.png)

![covid](./pics/newC.png)

And generate the predicted results:

![prediction](./pics/predictions.png)

