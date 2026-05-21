#Use an image that implements Lambda Runtime API
FROM public.ecr.aws/lambda/python:3.8   

#Copy application code and files
COPY app.js package*.json

#Install dependencies in the container
RUN npm install

#Function to run when Lambda function invoked
CMD [  "app.lambdaHandler" ]

