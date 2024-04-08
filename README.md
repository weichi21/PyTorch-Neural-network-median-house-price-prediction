## PyTorch Median House Price Prediction
- **Objective**: Leveraging deep learning architecture to construct a prediction model for median house prices.

`Dataset` can be downloaded/loaded using the func:`sklearn.datasets.fetch_california_housing` function. <br>

### Here I implemented:
1. Data Standardization
2. Create simple linear regression neural network
3. Create dynamic non-linear regression neural network for hyperparameter tuning
4. Comparing the convergence performance of different loss functions
5. Hyperparameter tuning and cross-validation of `hidden layers`, `number of neurons`, `activation function`, and `learning rate`
   
### Conclusion
- Best parameters: {'activation function': Tanh(), 'number of neurons': 16, 'hidden layers': 2, 'learning rate': 0.05}
- Best mean CV score (MAPE): 20.5663
- Test score (MAPE): 20.1813
- Test R2 Score: 0.792
- Average Accuracy: 79.82%
