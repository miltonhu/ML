<!DOCTYPE html>
<html>
<body>
<h1>Sentimental-Analysis</h1>
<!-- These paragraphs will be red -->
<h2>Introduction & Motivation </h2>

<p>During recent decades, there are a large number of public health problem existing in our life, hence for our project we are trying to explore how machine learning can help us solve these problems. Our main focus would be to discover adverse effects of Claritin with crowdsourcing (tweets on Claritin).  </p>
<p>Claritin is a combination of antihistamine and decongestant used to treat allergies, nasal congestion, and sinus pressure. Claritin is available over-the-counter and in generic versions. Claritin’s top 10 adverse events reported by FAERS to FDA include dizziness, drowsiness etc, no of events reported are not high enough to consider Claritin as a health concern.  </p>
<p>FAERS called FDA Adverse Event Reporting System, collects mandatory adverse event reports from drug manufacturers, and other medical professionals & consumers. In past drugs like Vioxx and fen-phen were withdrawn due to safety concerns as a result of Serious Adverse Events (SAEs) that were reported to the FDA through FAERS. Hence it is important to constantly verify the data reported to FAERS is correct.</p>
<h2>Overview of Data Set </h2>
<p>Datasets include tweets (on Twitter) that contained ‘Claritin’ for the month of October 2012. Contributors of data-set Dave Oleson & Crowd-Flower have applied some basic filtering for spam and this has left us with approximately 4,900 tweets. </p>
  
  <table >
  <tr>
    <td>Data Set Characteristics:</td>
    <td>Multivariate, Tex</td>
    <td>Number of Instances:</td>
    <td>4900</td>
    <td>Area:</td>
    <td>Medicine, Healthcare</td>   

  </tr>
  <tr>
    <td>Attribute Characteristics:</td>
    <td>Categorical,  Integer</td>
    <td>Number of Attributes:</td>
    <td>17</td>
    <td>Date Donated:</td>
    <td>Nov 13,  2013</td>    
    
  </tr>
  <tr>
    <td>Associated Tasks:</td>
    <td>Classification, Clustering</td>
    <td>Missing Values:</td>
    <td>Yes</td>
    <td>Techniques:</td>
    <td>NLP, Neural Network, SVM</td>
  </tr>
</table>
<p>Attribute Details: Categorical attributes include dizziness, convulsions, heart palpitations, shortness of breath, headache, drug effect decreased, allergies worse after taking a drug, bad interaction between Claritin and other drugs, nausea, insomnia. Demographic information includes ID, gender. Column such as relevance and  sentiment would serve as labels. </p>  
 
<p>We also have data reported to FDA for top 10 adverse effect of Claritin. Based on these data from these two sources we want to perform sentiment analysis on the Claritin effects.</p> 
  
<h2>Problem Statement</h2>  
<p>We hope to build a Machine Learning model that can forecast Sentiment score of the Twitter tweet. </p>  
  
<ul>
  <li>a.	Objective: Assign a Sentiment Score to the Claritin Tweet </li>
  <li>b.	Hypothesis: Total negative score of Claritin Tweets outperform the Side effects reported by drug producing companies to FDA</li>

</ul>  
  
<h2>Models & Technology</h2>
  
<p>According to the data characters and the model that we choose, the Natural Language Processing (NLP) will be applied.</p>  
<p>Based on NLP machine learning algorithm, we will focus on the following steps - Tokenization, Stemming, Lemmatization, Punctuation, Character count, Word count, Text classification and Deep learning for NLP, etc</p>  
  <ul>
  <li>a.	Visualization Libraries: Matplotlib, Seaborn </li>
  <li>b.	Model Libraries: SCIKIT-LEARN, TensorFLow, Stanford CoreNLP, spaCy  </li>

</ul>  
  



<p>REFERENCES :</p>
<p>https://www.figure-eight.com/data-for-everyone/</p>
<p>https://www.figure-eight.com/discovering-drug-side-effects-with-crowdsourcing/</p>
<p>https://machinelearnings.co/text-classification-using-neural-networks-f5cd7b8765c6</p>
</body>
</html>
