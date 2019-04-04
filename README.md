
# Tailored AWS Kubernetes Workshop with EKS, Envoy / Istio and AWS App Mesh

# Description

In this Kubernetes introductory workshop, you will learn about the features of Amazon's managed Kubernetes EKS. Background in EKS, Kubernetes, Docker, and container workflows are not required, but recommended. 
We will spend 2 hours hands-on exploring Kubernetes, EKS and open-source tools. Please bring your own laptop and sign up for a free trial account at https://aws.amazon.com/free/. 

In the workshop we will create an EKS cluster with eksctl, deploy the Kubernetes dashboard and a microservices based application. Then we will look into Helm to install a more complex application. 
In the last part of the workshop we will dive deeper into service meshes, install Istio with Envoy to apply cross cutting concerns to a polyglot application. To conclude, I will present a summary with a 5-minute outlook into the AWS App Mesh.

# Agenda

In this workshop we focus on a subset of a highly recommended and well designed Amazon EKS workshop by Brent Langston that you can find [here](https://eksworkshop.com/).

* Read [Introduction](https://eksworkshop.com/introduction/)


* [Start the workshop](https://eksworkshop.com/prerequisites/)


* [Launch using eksctl](https://eksworkshop.com/eksctl/)


* [Deploy example Microservice](https://eksworkshop.com/deploy/)


* [Helm](https://eksworkshop.com/helm_root/) ONLY COMPLETE installation part


then jump to 

* [Service Mesh with Istio](https://eksworkshop.com/servicemesh_with_istio/)

## Caution

Please make sure to tear down all ressources as described in the instructions. Stop the eks cluster using eksctl. Thank you.

## Additional ressources

There are some [supporting slides](https://speakerdeck.com/fmunz/istio-and-aws-app-mesh) for this workshop. 

If you are interested, you can find more slides about [getting started with containers in the cloud](https://speakerdeck.com/fmunz/getting-started-with-containers-in-the-cloud-404c9992-4f35-4f42-88bd-27c742895cc0). If you like, you can watch an [introduction to Istio on EKS video](https://www.youtube.com/watch?v=fDmJf9kWFws), a session that I presented at CODE One conference in late 2018. 


