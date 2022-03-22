## Venture Funding with Deep Learning

The purpose of this project is to create a neural network that uses the features contained in a dataset of companies who have received venture capital funding to determine if future companies will ultimately be successful or not. The data will need to be prepared and preprocessed before compiling and optimizing the neural network model. After evaluating and saving the model, two alternate models will be created to try to improve the original model's accuracy by adding more nodes to the first hidden layer of the model and increasing the number of epochs in the training regimen.

---

## Technologies

This project will be coded in Python. We will use multiple libraries and dependencies, including pandas, tensorflow, keras, and sklearn. 

---

## Installation Guide

These neural networks are built in a Jupyter notebook, and the code is fully executed. The original model is coded first and displays the summarized results of the accuracy and loss function. Following this model, the two alternate models are then coded and ran with their respective results displayed as well. All three models are saved as HDF5 files which makes them available to load and use again in the future.

---

## Usage

The Jupyter notebook will already be fully executed upon opening. The following shows a screenshot of the results of the three models. The first alternative model made very slight improvements in both accuracy and loss function by increasing the number of hidden nodes in the first layer of the model compared to the original model. The second alternative model doubled the number of epochs in the training regimen from 50 to 100. This model actually caused the loss function to increase and lowered the overall accuracy. Therefore, increasing the number of epochs alone does not produce a more accurate or efficient model.

![neural net results](https://raw.githubusercontent.com/tycastleberry/Challenge13/main/Neural_Network_Results.png)

---

## Contributors

Tyler Castleberry was the sole contributor to this project. 

---

## License

MIT License

Copyright (c) 2022 Tyler Castleberry

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.