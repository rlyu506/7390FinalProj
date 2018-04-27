# WHMC2018

The jupyter notebook can be run without a dataset since it does web scraping itself. Though, I still provide the dataset if you want to run it quickly for machine learning.

IAAF World Half Marathon Championship will be held in Valencia, Spain this year. It is an annual half marathon competition organized by the International Association of Athletics Federations, generally held every October. Prediction of this competition can provide a foresee to either athlete and audience. For the athletes, they could determine their further training strategy based on the prediction; for the audience, they would be more interested in the game, once the event draws more public attention, it will create more economic and cultural values. 

The winner and possible top ranks of the championship can be determined by the performance of athletes in former running competitions. The official website of IAAF provides the information of the registered athletes who has ever attended the half marathon held by IAAF, including their results of half marathon and other competition progression records. The goal of this project is to predict the result of 2018 world half marathon championship. To achieve it, first I did the data crawling and cleaning. Then I built a machine learning model based on the data and provide a prediction using the model. For data, I did web scraping to get the training dataset; for modeling, I set up spark structured streaming and used machine learning pipeline to build the model. I analyzed the data and chose to use decision tree as my algorithm to modeling, combined multiple factors together and predicted the performance time using the model. Also, to enhance accuracy, I tuned the model with ParamGridBuilder and CrossValidator. The result gives a list of athletes in sequence according to their ranking of performance in the prediction. It also gives the accuracy of the prediction model, which is acceptable for this project.


## License(MIT)
Copyright (c) 2018 by Ruofan Lyu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## License(CC)
This work is licensed under the Creative Commons Attribution 3.0 United States License. To view a copy of this license, visit http://creativecommons.org/licenses/by/3.0/us/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
