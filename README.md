# LDA_on_news
Performs LDA and other topic modeling on news stories to understand what subjects are being reported on.

## Conda environment
To reproduce the work easily, install Anaconda and create the environment:

`conda env create -f environment.yml`

The environment yml file is created like so:

`conda env export --no-builds | grep -v "prefix" > environment.yml`

## Data source

A big thanks to Andrew Thompson for collecting the data.  The full dataset is [here](https://components.one/datasets/all-the-news-2-news-articles-dataset/) and a smaller one [here](https://www.kaggle.com/snapcrack/all-the-news#articles1.csv).



