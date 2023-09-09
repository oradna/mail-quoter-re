# mail-quoter-re
A tool that uses AI to classify, read and extract key information from aviation reinsurance quote requests and automatically sends the mails to request a quote to underwriters and wholesale brokers.
The tool is designed for private use of my reinsurance brokerage firm. The tool must be able to monitor the mails and identify, using keywords or other methods, if a mail is an aviation reinsurance program quote request. 
Such mails include information about the aircraft make and model, year, pilots name, original insured name, as well as the policy expiry date, coverages needad and their limits, etc. 
Our tool must extract that key information and process it to make several functions: 
1) The tool Drafts a mail to underwritters asking for a quote request, using a tenplate that will be filled with the  information extracted from the mail we received as quote request. This mail will be reviewed by a human before being sent.
2) The tool  creates a database of the quote requests received, as well as a database of the aircraft, pilots, and policy information extracted from the mails received.
There is a web app with a user interface to adjust parameters and control the tool. For expample, what email adresses are being monitored, add edit or delete de templates, adjust the keywords, adjust the parameters being included in the databases of the xtracted information.
