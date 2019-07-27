# wordcloud
wordcloud in python

# File System
- data
    - templates: users' pictures
    - stopwords.txt: stopwords which you do not want
- fonts: users' fonts

- create_word_cloud.py: main function
- preprocess.py: preprocess the QQ chat records

# Usage
First install `jieba` and `wordcloud`:
`pip3 install jieba`
and
`pip3 install wordcloud`

Then run code in terminal:
`python3 create_word_cloud.py filename.txt`

If you want to generate the wordcloud of QQ chat record, first preprocess the text file:
`python3 preprocess.py filename.txt`

Then run the main code:
`python3  create_word_cloud.py __filename.txt`

For more details, read my blog post: [wordcloud](https://godweiyang.com/2019/07/27/wordcloud/)