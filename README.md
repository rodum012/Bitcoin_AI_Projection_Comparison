# Bitcoin AI Projection Comparison
A comparison of two neural network models fitted on 3 years of historic daily and weekly bitcoin pricing data used to project one year out into the future.

---

## Technologies

This application is written in Python v. 3.9.7 and makes use of
the following libraries:


[tensorflow](https://www.tensorflow.org/api_docs) was used to build neural network models

[yfinance](https://pypi.org/project/yfinance/) was used to download historic crypto data

[pandas](https://pandas.pydata.org/docs/) was used for data analysis and configuration

[numpy](https://numpy.org/doc/) was used for mathematical operations

[sklearn](https://scikit-learn.org/stable/) was used for scaling data

[matplotlib](https://scikit-learn.org/stable/) was used for graping historic procing data and future projections


---

## Installation Guide

Prior to running this application, perform the following in the command line to install the required libraries:

`pip install tensorflow`

`pip install yfinance`

`pip install pandas`

`pip install numpy`

`pip install sklearn`

`pip install matplotlib`

---

## Usage

In order to launch the application, navigate to the Bitcoin_AI_Projection_Comparison folder, open the 1dayLSTM.ipynb and 7dayLSTM.ipynb files, and run the cells to see the daily versuses weekly comparison of the LSTM models. Next, open Active_Learning.ipynb and run the cells to see the daily one year projections of the active learning model and open Active_Learning_Weekly.ipynb to see the projections for the weekly data. Additionally, in the ETH_Training.ipynb and cardano.ipynb files you can find the daily active learning model fitted to Ethereum and Cardano data as a comparison for how well the model works on other coins. Below is an example of the output of running the cells that shows a graph of the last 3 years of bitcoin data as well as a one year future projection using the active learning daily model that was the most accurate model in testing:

![Output](Images/ex_output.png)

---

## Contributors

Robby Odum, Kai Huang, Chance Griffin, Asia Perry, James Milan

Emails: rodum012@gmail.com, kaihuang0721@gmail.com, griffc5@unlv.nevada.edu, Asia.Perry02@gmail.com, cryptoklektik@gmail.com

---

## License

MIT