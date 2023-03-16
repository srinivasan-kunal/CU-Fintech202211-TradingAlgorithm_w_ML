# CU-Fintech202211-TradingAlgorithm_w_ML

This program combines python programing and machine learning to create an algorithm based trading bot that learns and adapts to new data in an evolving market. To this end the program compares the performance of multiple classification techniques to assess the best performing modeling technique for the OHLCV in emerging markets.

## Technologies
This program uses finta library to create several performance features in addition to the libraries installed previously.

---
## Installation Guide

To install `finta` use the following command in the dev environment.

```python
pip install finta
```

## Usage

The program compares the performance of a naive prediction strategy against the performance of alternative modeling approaches namely - Support Vector Machine (classification technique), logistic regression and decision trees.

It was observed that the performance of the model is better when at least a 6 month observation window is used as against a 3 month obersevation window. Among the alternative modeling techniques, SVC technique had the best performance in terms of accuracy and for predicting a one period improvement in returns. None of the alternative techniques performed significantly better in predicting a drop in one period reduction in returns.

---

## Contributors


Kunal Srinivasan

---

## License

2022 edX Bootcamps 