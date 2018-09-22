DataExtractor

A script built to extract data from reddit's online API for comments.

It is used to extract comments from files with the intent to build a chat bot
with machine learning using Google's TensorFlow.

Fully operational. See code for comments.

```
git clone https://github.com/velvetsnowman/RedditDatasetQuerying.git
cd RedditDatasetQuerying
```
Visit http://files.pushshift.io/reddit/comments/

Download any of the files you see. They are ordered by month, ie. RC_2005-12.bz2 are the comments for December 2005.

Once downloaded, extract the data and you should see a text file similar to RC_2005-12

You will need to change the file path in line 105 of DataExtractor.py to the extracted text file's path.

```
python DataExtractor.py
```
To view the data, view using TablePlus or DB Browser for SQLite

* This also helped me improve working with databases and querying
