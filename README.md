# Deep_Learning

## Project Overview
To import, clean, and preprocess the 'charity_data.csv' data, and create a deep learning model that is capable of predicting whether or not an applicant will be successful. The deep learning model ideally would achieve a target predictive accuracy higher than 75%.

## Resources
- Data Sources: charity_data.csv
- Software: Jupyter Notebooks, Python, Pandas, Tensorflow, StandardS caler, One Hot Encoder, SK Learn

## Summary
For the my model I used 8 nuerons in the first hidden layer and 5 in the secod hidden layer. This is because I used the number of variables, which was 7, and then added an extra one. I did the same for my second hidden layer, but I halfed the amount, which would be 4, plus 1, giving 5 nureons in this layer.  I used the Keras Dense class while making this model. All the hidden layers will use the Relu activation function, and the output layer will use the sigmoid activation function. 

I was not able to achieve the targed model performance. My model's accuracy was at 72.5%, which was close to the goal of 75%, but not quite there. Some of the steps I took to improve my score was increase the number of epochs from 50 to 100, which didn't do anything. The accuaury was still at 72.5%. Increasing the number of hidden layers, and the amount of nureons in thos hidden layers also did not improve the accuarcy. 

If I were to use a different model to solve this issue, I would use Random Forrest model. This is because it combines many smaller models to create a more accurate model, which help increase the accuracy. It is also a faster model that can help save time while making changes to the model. This can help make many changes to optimize the model in less time, than compared to the deep learning model which takes times to render.
