# AIDI1004-GCP
This is a demo on how to setup and deploy a web application on Google's GCP


# How to set this up. 

- Create a google account, login to https://console.cloud.google.com
- Setup a project and a billing account. 
- Download the gcloud command line tool from here: https://cloud.google.com/sdk/docs/install
- To deploy the application to GCP run 
    $ gcloud app deploy    
        
You can stream logs from the command line by running:
  $ gcloud app logs tail -s default

To view your application in the web browser run:
  $ gcloud app browse
