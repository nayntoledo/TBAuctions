# TBAuctions
TBAuctions Assessment 

Assessment: Building a Data Model
For an online auction platform, it's crucial to address both operational questions and business
improvement opportunities.
We aim to answer the following key questions:
- Who are our top buyers in terms of revenue?
- Which types of auctions are most successful?
- Who are our top-performing sellers in terms of revenue?
What do we need you to do?
- Create a Data Model: Design and implement a data model, including necessary SQL
transformations.
- Generate a Report: Produce a simple report utilizing the created data model
Note: This assessment is confidential and should not be shared (as well as your solution 😉)
We expect candidates to spend a maximum of 4 hours on this assignment.
💾 Data & Transform
You will be provided with a zip file containing:
- Auctions: A list of auctions and the associated seller
- Bids: A list of bids for various items
- Buyers: A list of registered buyers
💪 Your Task
Implement a solution that is able to:
- Data Cleaning: Clean the provided data and store the cleaned versions in a new folder.
- Data Transformation: Transform the data and create your dimension and fact tables. Organize
your data in multiple folders if needed, use medallion structure if possible.
- Star Schema: Convert the data into a star schema structure and establish the necessary
relationships.
- Reporting: Create a report based on the transformed data model.
Clean
Store the cleaned data in a folder named 'clean'.
Reporting
Split the data into a star schema.
Relationships
- bids.bidder = buyers.username
- auctions.auctionid = bids.auctionid
- 
🚀 To production
Develop a simple report demonstrating how you would present data to answer the specified questions.
￿ Additional requirements:
- The tool you use should work with SQL
- The solution should be in a form that can be stored in source control (git)
- The solution should be able to run on a local machine
- 
🍒 Bonus
- Implement some tests
- What more would you do with data if you had more time?

- Analytical Skills
- Performance Optimization
- Documentation and Communication
Good luck! 😀
