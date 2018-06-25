# New-Constructs-Data-Question

This class project was a collaboration with New Constructs, a financial analytics and technology company. 
## The objective is to read in SEC disclosure forms for publicly traded companies and to identify, extract, and classify data pertinent to determining whether or not a company intends to repurchase shares in their stock.
The problem is especially challenging since each filing is non-standarized format. 

Find Below the instructions provided to us:
#### Identify share repurchase activity in 10-K or 10-Q docs
1. For clarity, there won’t necessarily be separate paragraphs for each of those 7 data points we’ve identified (e.g., Share Repurchase Authorization Date, Share Repurchase Authorization, Share Repurchase Intention, etc.) - you could find each of those 7 data points all in a single paragraph depending on the disclosure in the filing. So if it made sense to, you could look at the problem in two stages - first, identifying those paragraphs generally that are about share repurchases, and second, classifying the data inside the paragraph into those 7 categories.

2. For the deliverable, please prepare a csv file with the data points that are included in share_repurchase_paragraphs.csv 

3. For errors, we’d prefer to err on the side of a false positive. I think those will also make for easier feedback than negative cases.

#### Other Relevant Files
1. nc_training_filings.zip, which contains the HTML filings for each of the items in the training set CSV we sent over (which I believe is a set of 500). That CSV includes accession_number, and all the HTML filings in that archive are named <accession_number>.html .
2. nc_validation_filings.zip, which contains the HTML filings for an extra 100 filings that aren’t in the training set. These are in case your students want to be able to try their models out on some unmarked data - we’ll provide feedback on those if they do.
3. nc_validation_filings.csv, which contains the ticker and accession number for the filings in #2.
