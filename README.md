# 51-pelton-mlproj-leadRealization
Analysis of leads that are turned definite in relation to words found in their corresponding traces

<strong>Colab Notebook</strong>
https://colab.research.google.com/drive/19U7Zansm18JzuQsoxz8gRbQY5oOErQnX?usp=sharing

> Definitely like the idea and think the business case if fairly clear. I think it would be nice if you were able to clarify your quality score a bit more. E.G. Is it 1-5, 0-100, qualitative, and what do those scores translate to in-terms of conversion rate.

<h2>Description of Metrics</h2>
The data used will include the status of each lead, and the body text of each trace associated with the lead.

<br/>
Not all words in the traces will be relavant, therefore, words that occure most commonly in leads that have been turned, lost, deffinite, or cancled will be extracted.

There are currently 55292 leads in the data set, of which 12543 are definite, 32156 are lost, and 105 are canceled.

Using this data, the model will be tested for predictive ability based on trace keywords.

If the model is successful, leads in jeoporday of being lost can be surfaced based on trace content.

> Is there any costs or treatment to resurfacing or re-engaging the leads in jeopardy? Would you consider a discount similar to how we had a pay-bump intervention for the confusion matrix in class?  More Curious than anything!
