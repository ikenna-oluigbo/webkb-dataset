# webkb-dataset
A modified selection of the WebKB dataset

### The original WebKB dataset can be downloaded from (http://www-2.cs.cmu.edu/~webkb/)

This directory contains modified relationship between the webpages such that it is suitable for Graph Analytics and other machine learning tasks. 

The webpages which were originally in string formats are now represented with unique node integer ID, and each edge represents a relationship between both nodes (webpages). 

The .content file remains unchanged, and contains descriptions of the webpages in the following format: 

		<webpage_id> <word_attributes>+ <class_label> 
    
These webpages are classified into one of the following five classes: 

			course 
			faculty 
			student 
			project 
			staff
