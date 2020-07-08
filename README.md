# aws-lambda-layer
Sample lambda layer to import npm dependencies to lambda functions

In the nodejs directory, install any dependencies needed in the lambda function.

Then zip up the nodejs folder and name it according to what you want your layer to be named.
Upload the zip file to s3, and create a new lambda layer using that bucket.
