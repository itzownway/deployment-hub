# deployment-hub

This repo acts as a central CI/CD controller.

## Purpose
- Trigger deployments for microservices
- Manage centralized deployment flow

## Connected Services
- simple-node-azure (Node.js app)

## Flow
Push → Trigger → Deploy to Azure





#### How We Can Deploy the - Other Git Repo Using this Deployment Hub 


    Step - 1
     
        - create the this repo 
         
        - create a  classic personal access token 

        - go to the created repo ----> Secret Key --- Paster this  - classic access token 


        - just push the code 

        - it will start deploy to - other repo 