Download Link: https://assignmentchef.com/product/solved-cs145-homework-6
<br>
In Homework 6, you will complete two basic text mining model in lectures: Naive Bayes and Topic modeling (pLSA). Python 3.6 is recommended in HW6 and you may need to install additional packages such as sklearn and jieba (numpy, pandas and matplotlib are also needed.) Besides, you are allowed to slightly change the code or add new functions other than “YOUR CODE HERE” as long as you keep the structure and do not use external model toolkits.

You need to submit all your python files, report and output files (including figures and text files). Do NOT include original dataset files.

<h1>1           Naive Bayes for Text</h1>

Naive Bayers is one generative model for text classification. In the problem, you are given a document in dataset folder. The original data comes from <a href="http://qwone.com/~jason/20Newsgroups/">“20 newsgroups”</a><a href="http://qwone.com/~jason/20Newsgroups/">.</a> You can use the provided data files to save efforts on preprocessing.

<ul>

 <li>Complete the implementation of Naive Bayes model for text classification in py. After that, run nbm sklearn.py, which uses sklearn to implement naive bayes model for text classification (Note that the dataset is slightly different).</li>

 <li>Report your classification accuracy on train and test documents. Also report your classification matrix. Show one example document that Naive Bayes classifies incorrectly ((you can fill in the following table).</li>

 <li>Question: Is Naive Bayes a generative model or discriminative model and Why? What is the difference between Naive Bayes classifier and Logistic Regression? What are the pros and cons of Naive Bayes for text classification task?</li>

</ul>

1

Introduction to Data Mining (UCLA CS 145)                                                                                            Homework 6

Table 1: Report accuracy for Naive Bayes Model

<table width="424">

 <tbody>

  <tr>

   <td width="165"> </td>

   <td width="133">Train set accuracy</td>

   <td width="126">Test set accuracy</td>

  </tr>

  <tr>

   <td width="165">sklearn implementation</td>

   <td width="133"> </td>

   <td width="126"> </td>

  </tr>

  <tr>

   <td width="165">your implementation</td>

   <td width="133"> </td>

   <td width="126"> </td>

  </tr>

 </tbody>

</table>

Table 2: Incorrect Examples

<table width="485">

 <tbody>

  <tr>

   <td width="285">Words (count) in the example document</td>

   <td width="112">Predicted label</td>

   <td width="88">Truth label</td>

  </tr>

  <tr>

   <td width="285">For example, student(4), education(2), etc</td>

   <td width="112">Class A</td>

   <td width="88">Class B</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Question: Can you apply Naive Bayes model to identify spam emails from normal ones? Briefly explain your method.</li>

</ul>

<h1>2           Topic Modeling: Probabilistic Latent Semantic Analysis (pLSA) (50 points)</h1>

In this section, you will implement Probabilistic Latent Semantic Analysis (pLSA) by EM algorithm.

<ul>

 <li>Complete the implementation of pLSA in py. You need to finish the E step, M step and likelihood function.</li>

 <li>Choose different <em>K </em>(number of topics) in py. What is your option for a reasonable <em>K </em>in dataset1.txt and dataset2.txt? Give your results of 10 words under each topic by filling in the following table (suppose you set <em>K </em>= 4).</li>

</ul>

Table 3: Topic words

Dataset 1

<table width="253">

 <tbody>

  <tr>

   <td width="63">Topic 1</td>

   <td width="63">Topic 2</td>

   <td width="63">Topic 3</td>

   <td width="63">Topic 4</td>

  </tr>

  <tr>

   <td width="63"> </td>

   <td width="63"> </td>

   <td width="63"> </td>

   <td width="63"> </td>

  </tr>

 </tbody>

</table>

Dataset 2

<table width="253">

 <tbody>

  <tr>

   <td width="63">Topic 1</td>

   <td width="63">Topic 2</td>

   <td width="63">Topic 3</td>

   <td width="63">Topic 4</td>

  </tr>

  <tr>

   <td width="63"> </td>

   <td width="63"> </td>

   <td width="63"> </td>

   <td width="63"> </td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Question: Are there any similarities between pLSA and GMM model? Briefly explain your thoughts.</li>

 <li>Question: What are the disadvantages of pLSA? Consider its generalizing ability to new unseen document and its parameter complexity, etc.</li>

</ul>