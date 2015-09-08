#Cover letter classification

###What?
I've been applying to jobs. Many jobs! I started thinking, is there a way to tell for sure which cover letters are more likely to get me hearing back from a company? The answer is, **probably**, and here's a shot at a model that can classify cover letters as successful (1) or unsuccessful (0). Eventually, I will use it to come up with an accuracy rate in classifying my own 30+ cover letters as 1 or 0.

In the file below, I am building a Multinomial Naive Bayes classifier. It is built off of the advice of [this page](http://nlp.stanford.edu/IR-book/html/htmledition/naive-bayes-text-classification-1.html) from Stanford's NLP department.

###Goal:
Successfully classify a cover letter as successful (hear back from a company) or unsuccessful (have yet to hear back...).

###How to use:
1. Make a directory containing all of your cover letters. These must be **.docx** files.
2. Append a 0 or a 1 to the filename, preceding the **.docx** part. This will indicate the success of the cover letter. For example, **Operations_Analytics_Analyst_1.docx**
3. Run **cover_letter_classification.R**. Input the path to the directory that you made in step 1.
4. If you're curious about the likely efficacy of a certain cover letter, try using the **test_doc_classify** function on a specific document.
