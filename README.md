# s3-presigned-url
Using s3 presigned url to upload file.

This repository include slides of S3 presentation, source code for BE and FE for Tech talk and blog at Saigon Technology.

Amazon S3: First look and simple demo to upload image to S3 with Presigned url[https://saigontechnology.com/blog/amazon-s3-first-look-and-simple-demo-to-upload-image-to-s3-with-presigned-url]
## 1. Install packages
Go to `aws-s3-demo-nodejs` and run `npm install` to install needed packages for server.

Go to `aws-s3-demo-react` and run `npm install to install needed packages for client.
## 2. Replace env variable
Replace your aws credentials and s3 bucket name.
## 3. Run server
Run `node index.js`.

This demo include 2 endpoint: GET for get existed file and POST for upload new file.
## 4. Run client
Run `npm start`
