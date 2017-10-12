This repo is for the paper:

Short-Term Traffic Forecasting Using Self-Adjusting k-Nearest Neighbours.

Regarding Short-Term Prediction by Self-Adjusting kNN (DP-kNN).

Some content will be updated later.

# Abstract
Short-term traffic forecasting is becoming more important in intelligent transportation systems. The k-nearest neighbours (kNN) method is widely used for short-term traffic forecasting.
However, kNN parameters self-adjustment has been a problem due to dynamic traffic characteristics. 
This paper proposes a fully automatic dynamic procedure kNN (DP-kNN) that makes the kNN parameters self-adjustable and robust without predefined models or training. 
We used realworld data with more than one-year traffic records to conduct experiments. 
The results show that DP-kNN can perform better than manually adjusted kNN and other benchmarking methods with regards to accuracy on average. 
This study also discusses the difference between holiday and workday traffic prediction as well as the usage of neighbour distance measurement.

# Usage
Code: to be updated. 

# Results
The results show that DP-kNN gives 9% to 40% improvement than benchmarking methods on average.

# Citation Request
**[IEEE Format]** B. Sun, W. Cheng, G. Bai, and P. Goswami, “Correcting and Complementing Freeway Traffic Accident Data Using Mahalanobis Distance Based Outlier Detection,” Teh. Vjesn., vol. 24, no. 5, Oct. 2017.

**[AAA Format]** Bin Sun, Wei Cheng, Guohua Bai, and Prashant Goswami 2017Correcting and Complementing Freeway Traffic Accident Data Using Mahalanobis Distance Based Outlier Detection. Tehnicki Vjesnik-Technical Gazette 24(5).

**[GB/T 7714]** SUN Bin, CHENG Wei, BAI Guohua, et al. Correcting and Complementing Freeway Traffic Accident Data Using Mahalanobis Distance Based Outlier Detection[J]. Tehnicki Vjesnik-Technical Gazette, 2017, 24(5).

**[Bibtex]:**

```tex
@article{sun2017correcting,
  title = {Correcting and {{Complementing Freeway Traffic Accident Data Using Mahalanobis Distance Based Outlier Detection}}},
  volume = {24},
  issn = {1330-3651},
  doi = {10.17559/TV-20150616163905},
  abstract = {A huge amount of traffic data is archived which can be used in data mining especially supervised learning. However, it is not being fully used due to lack of accurate accident information (labels). In this study, we improve a Mahalanobis distance based algorithm to be able to handle differential data to estimate flow fluctuations and detect accidents and use it to support correcting and complementing accident information. The outlier detection algorithm provides accurate suggestions for accident occurring time, duration and direction. We also develop a system with interactive user interface to realize this procedure. There are three contributions for data handling. Firstly, we propose to use multi-metric traffic data instead of single metric for traffic outlier detection. Secondly, we present a practical method to organise traffic data and to evaluate the organisation for Mahalanobis distance. Thirdly, we describe a general method to modify Mahalanobis distance algorithms to be updatable.},
  number = {5},
  journaltitle = {Tehnicki Vjesnik-Technical Gazette},
  shortjournal = {Teh. Vjesn.},
  author = {Sun, Bin and Cheng, Wei and Bai, Guohua and Goswami, Prashant},
  date = {2017-10}
}
```

# Paper
The paper full-text will be available on-line, open access: [Teh. Vjesn.](http://dx.doi.org/10.17559/TV-20150616163905).
The code is available on [GitHub](https://github.com/SunnyBingoMe/sun2017correcting-github).