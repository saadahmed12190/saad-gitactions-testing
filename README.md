This repo is used to do some testing on github action.
Our task includes:
-> Manually create ECS cluster.
-> Create a pipeline to build and deploy the nodeJS application to an ECS .  So you have to create a docker file for your application, build the image, push to ECR etc. You can pick any nodeJS application.
-> The authentication from github should be password less authentication.
-> The IAM should be configured in a way that it has least privileges as per the requirement.
