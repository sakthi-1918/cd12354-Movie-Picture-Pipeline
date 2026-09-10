# Project Screenshots Guide

Save your screenshots into this `screenshots/` folder using the following recommended file names:

| File Name | Description / What to Capture |
|---|---|
| `01-frontend-ci-pipeline.png` | GitHub Actions run of **Frontend Continuous Integration** showing green checkmarks for **Lint**, **Test**, and **Build** jobs. |
| `02-backend-ci-pipeline.png` | GitHub Actions run of **Backend Continuous Integration** showing green checkmarks for **Lint**, **Test**, and **Build** jobs. |
| `03-frontend-cd-pipeline.png` | GitHub Actions run of **Frontend Continuous Deployment** showing green checkmarks for **Lint**, **Test**, **Build & Push**, and **Deploy to Kubernetes**. |
| `04-backend-cd-pipeline.png` | GitHub Actions run of **Backend Continuous Deployment** showing green checkmarks for **Lint**, **Test**, **Build & Push**, and **Deploy to Kubernetes**. |
| `05-aws-ecr-backend-images.png` | AWS ECR Console showing the `backend` repository with images tagged with the commit Git SHA and `latest`. |
| `06-aws-ecr-frontend-images.png` | AWS ECR Console showing the `frontend` repository with images tagged with the commit Git SHA and `latest`. |
| `07-kubernetes-cluster-status.png` | Terminal output of `kubectl get pods,svc -o wide` showing both `backend` and `frontend` pods in `Running` status and both active LoadBalancers. |
| `08-backend-api-movies-response.png` | Browser window showing the Backend LoadBalancer URL returning the JSON movie list: `http://aeb025068f8124889985cab6b27469ba-1239211439.us-east-1.elb.amazonaws.com/movies` |
| `09-frontend-web-application.png` | Browser window displaying the Movie Picture website UI via the Frontend LoadBalancer URL: `http://a69188135b3534b01b938c5cd3cf971c-1007074040.us-east-1.elb.amazonaws.com` |
