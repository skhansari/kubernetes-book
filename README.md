## What is Kubernetes?
Kubernetes (k8s) is one of the fastest growing open-source projects that is reshaping production-grade container orchestration. Born out of the Borg project, which ran and managed billions of containers at Google, Kubernetes solves various technical challenges related to managing microservices, including service discovery, self-healing, horizontal scaling, automated upgrades and rollbacks, and storage orchestration. 

But what does Kubernetes have to do with IoT? Why should you care about an infrastructure tool?

It turns out that the benefits of Kubernetes—abstracting away cloud infrastructure and managing a microservice architecture—also helps alleviate the unique problems IoT solutions pose. By standardizing an interface for containers to run with little overhead at a low cost, Kubernetes can smooth over the operational burdens of deploying on the edge or in the cloud. 

This eBook starts with an overview of Kubernetes and walks through some of the lessons that the engineers at Leverege have learned running Kubernetes in production on some of the largest IoT deployments in North America. If you are considering a switch to using Kubernetes, or looking to spin up a new infrastructure practice, read on to evaluate the benefits of Kubernetes for your IoT deployment. 

## Table of Contents
**Chapter 1**: [Introduction to Kubernetes](chapters/%5BChapter%201%5D%20introduction.md)
- What is Kubernetes and how does it relate to Docker? In this chapter, we examine the evolution from Docker to Kubernetes, as well as a comparison of other container orchestrator products. 

**Chapter 2**: [Kubernetes Concepts](chapters/%5BChapter%202%5D%20concepts.md)
- Before diving into lessons learned with running Kubernetes in production, we walk through key Kubernetes concepts to illustrate why and how they are useful. 

**Chapter 3**: [Useful Tools](chapters/%5BChapter%203%5D%20tools.md)
- Kubernetes has garnered a rich ecosystem of tools that make working with Kubernetes easier. Here’s a list of useful tools that we’ve personally used. 

**Chapter 4**: [Monitoring](chapters/%5BChapter%204%5D%20monitoring.md)
- One of the challenges of running a massive microservice architecture is how complicated monitoring can be. This chapter provides options as well as installation tips to bootstrap a monitoring system in minutes. 

**Chapter 5**: [Deploying to Cloud Providers](chapters/%5BChapter%205%5D%20managed-services.md)
- Many cloud providers offer a managed instance of Kubernetes. This chapter compares the top three clouds’ Kubernetes products and recommendations for choosing one. 

**Chapter 6**: [Running GKE in Production](chapters/%5BChapter%206%5D%20gke-in-production.md)
- Leverege chose GKE to run some of the largest IoT systems to date. We share our rationale behind choosing GKE and some hard lessons learned along the way. 

**Chapter 7**: [Continuous Deployment](chapters/%5BChapter%207%5D%20continuous-deployment.md)
- After the first deployment, how do you set up a continuous deployment system for an efficient devops workflow? We share our experiences with popular tools and recommendations. 

**Chapter 8**: [Security](chapters/%5BChapter%208%5D%20security.md)
- Default Kubernetes setup is not secure. This chapter highlights open source tools and tips to use to secure your cluster. 

**Chapter 9**: [Disaster Recovery](chapters/%5BChapter%209%5D%20disaster-recovery.md)
- Kubernetes might be resilient, but a disaster recovery plan is still needed to protect against human errors and disk failures. Learn to set up back up processes for Kubernetes. 

**Chapter 10**: [Serverless](chapters/%5BChapter%2010%5D%20serverless.md)
- What happens when containerization and serverless frameworks converge? Evaluate your options for running serverless workloads on Kubernetes. 

## Contributing

We appreciate any efforts to improve the book. Please feel free to submit pull requests against relevant markdown files in 'chapters'
