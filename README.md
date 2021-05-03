# MultiFeature_FakeNews
Multiple Features based Fake News Detection using Article Performance.

## What is it and Why?
Over the past few years, many methods of fake news detection have been tested. Most of these methods rely on the content of the news title and article text to determine whether or not an article is genuine.

In our method, we have used multiple features apart from the news title and text which we call article performance features (APF) to more accurately detect and classify fake news.<br><br>
The following features have been used:<br>
<img src="https://github.com/mrushad/MultiFeature_FakeNews/blob/c6deed6fcfd956e0a9fa9c9d83a7c52f3ee85137/Reports%20and%20Pictures/Pictures/Features.png" alt="alt text" width="655" height="271">
<br>
More information can be found <a href="https://github.com/mrushad/MultiFeature_FakeNews/blob/69141beffe5ad5e9442521a5efc2a8de2cd02033/Reports%20and%20Pictures/Report/ML-Project-Report.pdf">here</a>.

## Getting Started

The entire project can be executed as a python notebook, the dataset is provided in the repository.


## Built With

* [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) - The notebook used
* [scikit-learn](https://scikit-learn.org/stable/) - For machine learning models and NLP
* [nltk](https://www.nltk.org/) - The natural language processing library
* [keras](https://keras.io/) - For deep learning models
* [numpy](https://numpy.org/) - For n-dimensional arrays
* [pandas](https://pandas.pydata.org/) - For data manipulation

## Results
The results have been summarized in the table and graph below:<br><br>
<img src="https://github.com/mrushad/MultiFeature_FakeNews/blob/d029bf611436ec24e11d28ba5af1906d5a6b3177/Reports%20and%20Pictures/Pictures/ComparisionTable.png" alt="alt text" width="762" height="242">
<img src="https://github.com/mrushad/MultiFeature_FakeNews/blob/d029bf611436ec24e11d28ba5af1906d5a6b3177/Reports%20and%20Pictures/Pictures/ComparisionGraph.png" alt="alt text" width="570" height="288">
<br>
As we can see, the inclusion of APF gives an increase in accuracy in all models tested.
