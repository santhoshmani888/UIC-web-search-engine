Instructions to run code:
1.install all dependencies from requirements.txt (pip install -r requirements.txt)
2.extact code folder to work directory, if extracted in different folder(other than work directory) pass the path code folder as sys variabe.
3.run ui.py or ui.py "code folder path"
4. GUI will be prompted for input.

Notes:
1.some parameters used:
Crawling is done for 5000 page, beta for page rank =0.85, root node =cs.uic.edu

2.Folder consists of  page rank for all 5000 docs in json format. other important files are pickled.

3.to run from scratch - run in the following order
 a.crawler.py
 b.tfidf.py
 c.pagerank.py

 d.ui.py
