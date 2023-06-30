The purpose of thi repository is to build many machine learning models for online analysing and forecasting  volatility some companies, getting data from  AlphaVantage API. Clearly, we are going to build four model's types :

1 - A GARCH model or any type of time serie model (depending to data), then we will learn all parameters by native algorithms from Scikit-Learn python package.

2 - A GARCH model or any type of time serie model (depending to data), but with parameters learned by a bayesian algorithms. We are going to reformulate these models using hidden Markov models (also called state space systems) and will use algorithms like particle filtering with unknowed parameters, particle Gibbs algorithm, etc ...

3 - Reccurent Neural Network (RNN) applyed  to these series of datas. Network will be learned by native algorithmsTensorFlow python package (Gradient Descent)

4 - Same RNN but we expect to try a different perpective to learn all parameters of network by using particle techniques.

Then we will make comparisons of these models.