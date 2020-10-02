# Notes:

[Source](https://jovian.ml/learn/data-analysis-with-python-zero-to-pandas)

[Link](https://jovian.ml/aakashns/zerotopandas-course-project-starter)

#### Step 1: Select a real-world dataset

* Find an interesting dataset on this page: [https://www.kaggle.com/datasets?fileType=csv](https://jovian.ml/outlink?url=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%3FfileType%3Dcsv)

* Download the dataset using the [`opendatasets` Python library](https://jovian.ml/outlink?url=https%3A%2F%2Fgithub.com%2FJovianML%2Fopendatasets%23opendatasets)

```python
#Here's some sample code for downloading the US Elections Dataset:

import opendatasets as od
dataset_url = 'https://www.kaggle.com/tunguz/us-elections-dataset'
od.download('https://www.kaggle.com/tunguz/us-elections-dataset')

#You can find a list of recommended datasets here: https://jovian.ml/forum/t/recommended-datasets-for-course-project/11711
```

#### Step 2: Perform data preparation & cleaning

- Load the dataset into a data frame using Pandas
- Explore the number of rows & columns, ranges of values etc.
- Handle missing, incorrect and invalid data
- Perform any additional steps (parsing dates, creating additional columns, merging multiple dataset etc.)

#### Step 3: Perform exploratory analysis & visualization

- Compute the mean, sum, range and other interesting statistics for numeric columns
- Explore distributions of numeric columns using histograms etc.
- Explore relationship between columns using scatter plots, bar charts etc.
- Make a note of interesting insights from the exploratory analysis

#### Step 4: Ask & answer questions about the data

- Ask at least 4 interesting questions about your dataset
- Answer the questions either by computing the results using Numpy/Pandas or by plotting graphs using Matplotlib/Seaborn
- Create new columns, merge multiple dataset and perform grouping/aggregation wherever necessary
- Wherever you're using a library function from Pandas/Numpy/Matplotlib etc. explain briefly what it does

#### Step 5: Summarize your inferences & write a conclusion

- Write a summary of what you've learned from the analysis
- Include interesting insights and graphs from previous sections
- Share ideas for future work on the same topic using other relevant datasets
- Share links to resources you found useful during your analysis

#### Example Projects

Refer to these projects for inspiration:

- [Analyzing StackOverflow Developer Survey Results](https://jovian.ml/aakashns/python-eda-stackoverflow-survey)
- [Analyzing Covid-19 data using Pandas](https://jovian.ml/aakashns/python-pandas-data-analysis)
- [Analyzing your browser history using Pandas & Seaborn](https://jovian.ml/outlink?url=https%3A%2F%2Fmedium.com%2Ffree-code-camp%2Funderstanding-my-browsing-pattern-using-pandas-and-seaborn-162b97e33e51) by Kartik Godawat
- [WhatsApp Chat Data Analysis](https://jovian.ml/PrajwalPrashanth/whatsapp-chat-data-analysis) by Prajwal Prashanth
- [Understanding the Gender Divide in Data Science Roles](https://jovian.ml/outlink?url=https%3A%2F%2Fmedium.com%2Fdatadriveninvestor%2Fexploratory-data-analysis-eda-understanding-the-gender-divide-in-data-science-roles-9faa5da44f5b) by Aakanksha N S
- [2019 State of Javscript Survey Results](https://jovian.ml/outlink?url=https%3A%2F%2F2019.stateofjs.com%2Fdemographics%2F)
- [2020 Stack Overflow Developer Survey Results](https://jovian.ml/outlink?url=https%3A%2F%2Finsights.stackoverflow.com%2Fsurvey%2F2020)