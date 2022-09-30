A Corporate credit rating is an assessment of the creditworthiness of a Investment 
company, often a investor’s status with respect to a particular investment made in a 
corporate company. This assessment is based on comprehensive, defined rating 
methodology, and rating criteria. Credit ratings are judgments of investor based on relevant 
risk factors, expressed by a letter-grade or number-grade rating symbol that markets depend 
on for differentiating between different risk levels of a company.
Credit ratings have become one of the primary references for investors to assess and 
reduce possible risks, and make on-point decisions before investing in a company.
Data Scraping (Python- Beautiful Soup), Fetching data from a database, statistical 
analysis and machine-learning models on PySpark, have been deployed to evaluate 
corporate credit risk in this project.

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


Data Description and Technologies Implemented
Data Description
Below are the data Sources used for extracting the data:
Corpdatahub for data extraction.
  Data present on this source was in tabular format and hence we need to scrap tables from this data source.
  There is a separate file for company data and rating history from various agencies. So there 
in total 2 files after the successful gathering having 7k+ and 400k+ records respectively.
Also each file contains below mentioned information :
• Rating history : Rating agency, Company name, Date of Rating, Ratings (past 
ratings)
• Company data : Name, Symbol, Sector, Industry


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++



Financial modeling prep API for Financial ratios data
extraction.
Data gathered from this source is received in “json” format and stored in pandas 
dataframe which was then ingested to mongoDb database.
In total we gathered a single file having below mentioned information :
• Liquidity measurement ratios
• Profitability indicator ratios
• Debt ratios
• Operating performance ratios
• Cash flow indicator ratios
• Investment Valuation ratios
