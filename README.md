#  Religious Hate Speech Annotations for Arabic Tweets

This repo contains both training (```train.csv```) and testing (```test.csv```) datasets used in our paper. As per [Twitter's Developer Policy](https://developer.twitter.com/en/developer-terms/policy), we are only allowed to publicaly share tweet ids along with its annotaion (1 = hate , 0 = not hate). Full tweets (except for those that have been deleted or made private) can be obtained by hydrating tweet ids using tools such as [twarc]( https://github.com/edsu/twarc).

We also provide three Arabic hate term lexicons. Each term is assigned a positive or a negative real-valued score.  positive scores represent positive association with hate class, while negative scores reflect negative assocation with hate class. 
1. ```AraHate-PMI.csv```: Hate scores were assigned based on the Pointwise Mutual Information (PMI) metric.
1. ```AraHate-CHI.csv```: Hate scores were calculated using the chi-square statistic. 
1. ```AraHate-BNS.csv```: Hate scores were computed using the Bi-Normal Separation (BNS) method.  

Finally, we provide a list of 330 Arabic stop words (```stop_words.csv```).  

Please cite our paper if you find any of our data helpful for your research: 

```
@inproceedings{,
  title={},
  author={},
  booktitle={},
  pages={},
  year={},
  organization={}
}
```
