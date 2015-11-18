<img src="http://ypereirareis.github.io/assets/images/posts/docker.svg" />

# Docker DynamoDB

Build for AWS DynamoDB local.

## What's DynamoDb

Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. You can use Amazon DynamoDB to create a database table that can store and retrieve any amount of data, and serve any level of request traffic. Amazon DynamoDB automatically spreads the data and traffic for the table over a sufficient number of servers to handle the request capacity specified by the customer and the amount of data stored, while maintaining consistent and fast performance. 

__to start your local Dynamo, run:__



*Feel free to add parameters:*


[AWS DynamoDB Docs](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

## What it uses

 * __NodeJS__ with Node Package Manager
 * __[Dynalite](https://github.com/mhart/dynalite)__ - thanks to [@mhart](http://www.github.com/mhart) to make it possible.


__to start your local Kinesis, run:__

`docker run -d -p 8080:8080 vsouza/dynamo-local --port 8080`

*Feel free to add parameters: ( see Kinesalite [doc](https://github.com/mhart/dynalite) )* 

`docker run -d -p 8080:8080 vsouza/dynamo-local --port 8080 --path .`

## License
[MIT License](http://vsouza.mit-license.org/) © Vinicius Souza

<img src="contribute.png" />
