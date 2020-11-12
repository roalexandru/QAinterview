# QAinterview

Task:
Using the Community UiPath (Studio + Orchestrator) version create a workflow (or more) that solves the following tasks:
Process 1: 
-	Navigate to emag.ro in laptops section sorted by the number of reviews (https://www.emag.ro/laptopuri/sort-reviewsdesc/c)
-	Scrape the top 100 entries (including information about the product name, price, and review score)
-	Upload every laptop as a transaction in an Orchestrator Queue named “Laptops”
Process 2:
-	Retrieve the data from the Orchestrator Queue
-	Find the best 3 laptop by the review score
-	Export the top 3 laptops in a CSV file that contains the laptop name, price and the score


Resources:
- demo project : https://github.com/roalexandru/QAinterview/blob/main/DemoQA.zip
-	https://cloud.uipath.com (signup for community – Orchestrator and Studio)
-	https://docs.uipath.com/studio
-	https://docs.uipath.com/orchestrator/
-	https://docs.uipath.com/orchestrator/docs/about-queues-and-transactions
-	https://docs.uipath.com/activities/docs/write-csv-file
