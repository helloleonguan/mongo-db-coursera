## Week 1: Getting Started with MongoDB & Basic Data Analysis
- Use the Aggregation Framework to analyze data stored in MongoDB
- Create and connect to a MongoDB Atlas cluster from Python
- Import CSV data into a MongoDB cluster from the command-line

### MongoDB Document Model
- Documents in MongoDB store hierarchical data (something like JSON)
- each field is a key-value pair
- value can be 
	- scalar values, strings
	- arrays
	- documents

### MongoDB Structure
- A cluster contains multiple databases. 
- A database contains multiple collections.
- Multiple documents form a Collection.

### Aggregation Framework 
- input: a collection
- various stages (pipeline)
- output: a stream of documents

### MongoDB Operators
- [connection string for MongoDB](https://docs.mongodb.com/manual/reference/connection-string/)
- [$group and its accumulators](https://docs.mongodb.com/manual/reference/operator/aggregation/group/index.html?jmp=coursera-intro-mongodb#pipe._S_group)
- [$sort](https://docs.mongodb.com/manual/reference/operator/aggregation/sort/)
- [$sortByCount](https://docs.mongodb.com/manual/reference/operator/aggregation/sortByCount/)
- [$facet for multiple pipelines](https://docs.mongodb.com/manual/reference/operator/aggregation/facet/index.html)


 