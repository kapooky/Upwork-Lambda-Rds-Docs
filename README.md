# Lambda-Aurora-EFS Production CI/CD Pipeline

AWS pipeline that builds & deploys .Net container images into AWS Lambda. Complete with staging, test, and production environments. 

### Pipeline Architecture 
Attached image to showcase the pipeline working. 
<img src="https://raw.githubusercontent.com/kapooky/Upwork-Lambda-Rds-Docs/blob/main/cloudformation-parameters.png" width=640>


### Files Overview

Below contains a list of all the new files that have been added. 
- **application-infrastructure.yaml** - Cloudformation template for environment-specific resoruces (Lambda,EFS,Aurora,VPC's,etc) 
- **pipeline.yaml** - Cloudformation template for the pipeline. 
- **codebuild-dev.yaml** - Configuration file for the dev-Codebuild action.
- **codebuild-testing.yaml** -  Configuration file the testing-Codebuild action. 


### Prerequisites

Github-instructions 
You will need a Github-OATH token:
Follow these instructions and keep the token safe. We will need it later on. 
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
Note: Please ensure you are the owner of the repository that is being sourced. 
There are 2 possible ways to deploy this pipeline. The easiest way



## Deployment Instructions


### Prerequisites


