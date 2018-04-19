# node_direct_s3_uploader

just an example

creat *.env*
```
PORT = 3001

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=us-east-1

S3_BUCKET=
```

```
npm i
node app.js
```

```http://localhost:3001/```

Choose File and upload any picture, the avatar should reload after few seconds.

To confirm, you should see the file into the S3 bucket or you can also right click on the new avatar picture and *Copy Image Address*

