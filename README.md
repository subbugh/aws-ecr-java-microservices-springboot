# aws-ecr-java-microservices-springboot
Usage of AWS – ECR (Elastic Container Registry) and deploy a Docker Image – Hands-on guide:
-------------------------------------------------------------------------------------------

Detailed steps are enclosed in the attached documents "AWS_ECR_CaseStudy.pptx" and "AWS_ECR_CaseStudy.pdf".

Pre-requisites:
---------------
1. Docker Desktop installed, on your local system.
2. A working, Java Microservices project on your local system, with the Dockerfile setup. Create a local Docker Image using a Dockerfile. The same Docker image can be used for tagging, pushing and testing on ECR. 
3. For detailed hands-on guide including the steps, screenshots and code base for the above points 2 and 3, please refer to my below URL’s.

    https://github.com/subbugh/java-microservices-springboot-docker-dockerhub

    https://github.com/subbugh/java-microservices-springboot-docker

    https://github.com/subbugh/java-microservices-springboot

Steps: This document is to guide you to push an image to AWS-ECR and deploy the same:
-------------------------------------------------------------------------------------
1. Log into AWS Console.
2. Create ECR Repository.
3. A local Java Microservices application and Docker setup on your desktop. (Refer to "Pre-requisites" section)
4. Create a local Docker image, using a Dockerfile. . (Refer to "Pre-requisites" section)
5. Log into AWS – ECR, through a terminal.
6. Tag the local docker image, to push to the ECR.
7. Push the tagged docker image into the ECR Repository.
8. Run the pushed image and test it on the Browser, for the expected results.



