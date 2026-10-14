CI/CD Assignment – Task 2
For this assignment, I created an automated Docker pipeline using GitHub Actions.
The goal was to build a simple website, package it into a Docker image, and automatically publish that image to GitHub Container Registry (GHCR).

I wanted to understand how DevOps engineers automate repetitive tasks instead of building and publishing everything manually.

What I Built
Created a simple HTML website.
Created a Dockerfile using NGINX.
Created a GitHub Actions workflow called docker.yml.
Configured the workflow to run automatically when changes are pushed to the main branch.
Automated the building and publishing of my Docker image.
Successfully published the image to GitHub Container Registry.
Tools and Technologies
GitHub
GitHub Actions
Docker
NGINX
HTML
GitHub Container Registry (GHCR)
YAML
How My Pipeline Works
I push changes to my GitHub repository.
GitHub Actions automatically starts the workflow.
The workflow downloads my project files.
Docker builds an image containing my NGINX website.
GitHub Actions publishes the image to GitHub Container Registry.
Testing and Results
I checked the GitHub Actions page to confirm that my workflow completed successfully.

The build-and-push job passed with a green tick, and the workflow completed in approximately 28 seconds.

I then checked GitHub Packages and confirmed that my Docker image was published successfully with the latest tag.

Published Docker image:

ghcr.io/samatar17/devops-learning:latest

Challenges and What I Learned
One challenge was understanding where to place the GitHub Actions workflow. I learned that workflow files must be saved inside .github/workflows.

I also learned how to connect GitHub Actions to GitHub Container Registry and configure permissions for publishing Docker images.

By checking the workflow results and published package, I gained a better understanding of how automated pipelines work.

Evidence
I captured screenshots showing:

Successful GitHub Actions workflow runs.
Successful Docker build-and-push job.
Docker Build summary.
Published Docker image in GitHub Packages.
Conclusion
I successfully completed Task 2 by creating a working automated Docker build-and-publish pipeline.

This assignment helped me improve my understanding of Docker, GitHub Actions, YAML configuration, and continuous delivery.

I'm continuing to build my practical DevOps skills, one project at a time.

