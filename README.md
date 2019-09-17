## Lab: Lambda Functions
AWS Lambda allows writing code that is triggered in the cloud, without thinking about maintaining servers. We’ll use it today to automatically run some processing on image files after they’re uploaded in TaskMaster.

## Featured Tasks
- [x] A user should be able to upload an image at any size, and have both the original size and a thumbnail size associated with the task in question.
- [x] When an image is uploaded to your S3 bucket, it should trigger a Lambda function. (That Lambda function may be written in any language.)
- [x] That function should create a 50x50 pixel thumbnail version of that image, and save it to another S3 bucket. It should do so with a predictable naming convention, so that your server and/or frontend know where that thumbnail image will be.

## Works Cited
[AWS Tutorial](https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html)  
[How to Give your uploads public access](https://forums.aws.amazon.com/thread.jspa?threadID=116231)

## Collaborative Efforts 
Trevor Dobson