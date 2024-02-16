# walmart_sales_neural_network
I attempted to build a neural network that predicts weekly sales at various Walmart stores given various features such as the date, unemployment rate, consumer price index, whether or not it was a holiday, average fuel price, and more. 

For comparison, I first built a LassoCV model which had an r2 score of 0.155.

I then built a Random Forest Regression which managed to score an r2 score as high as 0.947, but with a Mean Absolute Error of roughly 60,000.

To further minimize that error, my natural network utilized five hidden layers with 279 nodes each to arrive at an r2 score of 0.985 and an MAE of roughly 44,000. I could live with that! 

Considerations for future models are located at the bottom of the ANN notebook.
