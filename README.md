# Assignment

To upload, connect, query the data to and from the DynamoDB table using NodeJS SDK

## Getting Started

If you are a beginner, you can use this assignment to gain hands-on knowledge on using AWS DynamoDB.
This is a basic and simple implementation, and it is simple to comprehend.

### Prerequisites

- Basic Understanding of AWS concepts
- Access to AWS free tier account
- Basic understanding of Javascript

### Steps involved

A bunch of following simple steps will make you able to handle multiple items in a DynamoDB table.

Create a AWS free tier account:

```
https://aws.amazon.com/
```

Create a DynamoDB table using management console.


Add item/items into the DynamoDB table usign management console. At this step, you will be assured of continuing this assignment as the following steps will let you add multiple items to the table in no time.


Create a Cloud9 environment to let our NodeJS EC2 instance connect our input file to DynamoDB table. In this case, a JSON file serves as the input file therby providing us with the list of items to be uploaded.
I had used Atom IDE instead od cloud9, but the Remote-edit package required to do the connection is not working. Hence the switch to AWS Cloud9, which is simple too. 


Create a S3 bucket as a resource to provide us with out JSON content.

In you Cloud9 IDE, open the editor, use the code added in this repository. Don't forget to edit/modify the code as per your DynamoDB table name, S3 bucket name.

Successfully implement the above steps using the details documentation provided:

```
PranitaDynamoDB/Pranita DynamoDB documentation.docx
```

## Help gathered

AWS Javascript SDK documentation

```
https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/DynamoDB.html
```

Other widely available resources on the internet






