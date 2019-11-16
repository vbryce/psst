# psst
# Proof of concept app that returns trust / responsibility related data for a company.
# Trigger action is an SMS, or form field on website.
# Predefined library links company names to twitter handle, trustpilot, glassdoor, CSRhub.
# (To add - fuzzy match to library name)
# Returns naturalistic statements about the company based on values returned.
# Aim: an SMS based service that summarises trust/responsibility related data about a company.
# Use cases: thinking of applying for a job. Thinking of buying a product. Want to find out more about a company.
# Modules:
# o	SMS trigger
# o	Confirm target company
# o	Get glassdoor rating
# o	Get trustpilot rating
# o	Get CSRhub rating
# o	Get twitter sentiment
# o	Get twitter keywords
# o	Web frontend
# o	SMS output
# o	[Optional: replicate the workflow via voice]
# o	[Optional: aggregate ratings into a good/evil rating]

# Requirements:
# •	Twilio account & credit
# •	UIPath
# •	Twitter API key
# •	Sentiment analysis library
# •	Company names library / lookup
# •	(optional) website - domain.com

# Notes
# Uses twitter standard API, limited to last 7 days and based on a sample (incomplete)
# Company library /lookup is limited to Fortune1000/FTSE100 with gaps
# Twilio is in trial and will only send to approved numbers & with trial message.

# TO DO: [1]outline Twilio workflow. [2]UIPath to pull ratings from web. [3]Python module to get twitter sentiment and keywords. [4] target company confirmation via fuzzy lookup.
