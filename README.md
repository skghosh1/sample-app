# sample-app
**Creating a simple CI/CD pipeline using Cloud Source Repositories, Artifact Registry, and Cloud Build.**

Creating a GKE cluster based on a set of configurations provided.
![Alt text](images/pods.png)

Creating a GItHub Repository to host your Go application code.
![Alt text](images/GitHubConnect.png)

Creating Cloud Build Triggers that deploy a production and development application.
![Alt text](images/triggers.png)

Pushing updates to the app and creating new builds.
![Alt text](images/build-history.png)

Expose the production-deployment deployment on the prod namespace to a LoadBalancer service named prod-deployment-service on port 8080, and set the target port of the container to the one specified in the Dockerfile.
![Alt text](images/LB.png)

Building Artifacts:
![Alt text](images/AR.png)

Rolling back the production application to a previous version.
![Alt text](images/Rebuild.png)

Final web page:
![Alt text](images/wb.png)
