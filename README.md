This project is designed to approximate conversion lift for a digital marketing campaign using DoubleClick Campaign Manager (referred to as CM).  We use CM's viewability technology, and calculate conversion rate for users that were exposed to, but did not view impressions.  The users that did not view any exposed impressions are treated as our control group, and users that do view impressions are treated as the test group.  This process does introduce bias, which is why this is labeled as an approximation, and does not replace the true value of a controlled test. 

However, this process can be applied on historical data, and bares no additional cost.  All that's needed is the raw logs from CM, as well as a connection to BigQuery.

Data from this notebook represents dummy client data. 