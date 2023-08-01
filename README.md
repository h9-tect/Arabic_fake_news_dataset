# Arabic_fake_news_dataset

### Please note that this dataset needs more preprocessing.

## Introduction

This repository contains the `Arabic_fake_news_dataset`, a collection of news articles scraped from the Egyptian platform [متصدقش (Matsda2sh)](https://matsda2sh.com/). The dataset is intended for studying and addressing the spread of fake news within the Egyptian community. It includes news articles classified as either fake or true, along with their corresponding titles.

## Dataset Details

- The dataset is provided in the form of a JSON file named `arabic_fake_news_dataset.json`.

- The JSON file contains a list of dictionaries, where each dictionary represents a news article and has the following key-value pairs:

  - `link`: The URL of the news article.
  - `fakes`: A list of strings representing fake news titles associated with the article.
  - `trues`: A list of strings representing true news titles associated with the article.

- The data was collected through web scraping from the [متصدقش (Matsda2sh)](https://matsda2sh.com/) platform, which focuses on the dissemination of fake news within the Egyptian context.

## Preprocessing Note

It is essential to note that the dataset may require preprocessing steps to ensure the data's quality and consistency for use in various natural language processing (NLP) tasks. The suggested preprocessing steps include, but are not limited to:

- Removing duplicate entries to avoid data redundancy.
- Handling missing or incorrect data, if any.
- Removing noise or irrelevant information that might have been introduced during web scraping.
- Tokenization and text normalization to prepare the text for downstream NLP tasks.

## Citation

If you use this dataset in your research or projects, we kindly request you to cite the source:


@misc
{Arabic_fake_news_dataset,
  title = {Arabic_fake_news_dataset},
  author = {Hesham Haroon, Matsda2sh},
  year = {2023}
}



## Disclaimer

This dataset is provided for research purposes only. The authors and contributors of this repository do not guarantee the accuracy or reliability of the information in the dataset. Users are advised to exercise caution and conduct their own verification and validation processes.

## Acknowledgments

Special thanks to the team at [متصدقش (Matsda2sh)](https://matsda2sh.com/) for providing the data and making it accessible for research purposes.

### Happy NLP Research!
