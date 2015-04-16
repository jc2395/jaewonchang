This is readme file for Jae Won Chang's assignment 3.
This assignment was about analyzing the relationship between idoelogy and words. In order to do that, I suppose to build a validated model of words and ideology of the speaker. 
Prior to begin, it is necessary to download the congressional research from the Sunligh API at https://gist.github.com/soodoku/85d79275c5880f67b4cf
In terms of merging, you can use preprocessData.py at https://github.com/soodoku/Text-as-Data/blob/master/preprocess_csv/preprocessData.md
The next step is downloading ideology records from voteview.com (DW-Nominate, 1st dimension).
For the rest of the commands, jaewon assignment3 file will provide you. I tried to merge documents regards to speaker's last name. The script successfully calculated trigrams but somehow it did not show the bigram. Furthermore, it may have some mistake in coding of creating arrays of the frequentcy of ngrams in to arrays, and creating array of the speakers' ideology scores. If I could coding correctly, it should show the arrays of frequency of bi/trigrams of speakers in the x variable and ideology scores form in the y. 
As I have trouble with this process, I could not make further steps to make Lasso model. 
