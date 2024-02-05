# Cryptocurrency_direction_prediction

This project is my take to replicate findings from the study on cryptocurrency prediction direction paper.
Name of the paper is: Prediction of Cryptocurrency Returns using Machine Learning by Akyldrim et al.(2021).
Link to the paper: https://link.springer.com/article/10.1007/s10479-020-03575-y

In this study, we considered twelve cryptocurrencies and studied their predictability using machine learning classification algorithms over two different time scales. (Daily and 15-min returns)

We have used three different classification algorithms:
- Logistic Regression, 
- Support Vector Machines
- Feed Forward Neural Network 

to demonstrate the predictability of the upward or downward price movements. The best performing and robust models in the prediction of the next day’s return, is the feed forward neural network with consistently above 50% fit, low variation across all the products and different timescales.

Although the performance of classification algorithms are not uniform over different tokens, many occasions predict accuracy with over 65%. The results indicate that the use of machine learning is promising for short term forecasting of trends in the cryptocurrency market.

Finally, the predictive accuracy is not too volatile across different forecasting horizons.

Findings have important implications with regards to market efficiency. First, if the cryptocurrency markets were efficient in the weak form, their past price movements would not help us to forecast the future returns. However, our findings imply that applying machine learning tools on historical prices enables one to predict cryptocurrency returns with successful accuracy at the intraday level.

Considering the fact that financial markets have significantly evolved over the past decade, driven by new technologies in automated trading and financial infrastructure, our finding is particularly important for algorithmic trading purposes. Deciding when to buy and sell cryptocurrencies within the day can be successfully automated with the application of machine learning algorithms. The success of such newly developed algorithms might also cause more high-tech dominant financial markets. Lastly, even though cryptocurrency markets are far from being regulated, policy makers will still need to pay attention to these markets.
