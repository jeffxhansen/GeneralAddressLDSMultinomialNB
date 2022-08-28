# GeneralAddressLDSMultinomialNB

This was a project for my LING 581 (Natural Language Processing) class at BYU my junior year.
In this class, we surveyed many different Machine Learning models and analyzed their application and success on various Natural Language Processing (NLP) tasks.
We read weekly scholarly articles and the most recent and substantial developments in many different NLP tasks.
We each took on a semester long research/programming project to solve some novel NLP task.

I chose to solve author identification for speakers for the Church of Jesus Christ of Latter-Day Saints. 
After preprocessing a corpus of every general address given in the LDS Church, I used TF-IDF vectorization of the words to get frequency counts for each speaker.
I then trained a Multinomial Naive-Bayes model (using sklearn) on this vectorization to accomplish the author identification task.
I proposed that tokenizing scripture references and quotation references would boost accuracy.
My process and findings are written in the four-page scholarly article in this github repo.
In the end my model performed at a 82% accuracy, and I also demonstrated that including tokenized scripture references and quotation references boosted accuracy and performace.
