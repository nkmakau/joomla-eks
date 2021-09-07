# Joomla, MySQL Deployment on AWS-EKS

This is a task used to practice deployment to AWS EKS. We will come to know How to deploy Joomla, MySQL, Prometheus and Grafana on AWS EKS.

We will perform the following tasks:
1.	We are going to create a Kubernetes Cluster in AWS EKS
2.	We will configure Kubectl in our system in order to communicate with our cluster.
3.	Then we are going to deploy Joomla web-app with MySQL database in cluster with Application Load balance(ALB) using Kustomization YAML file.
4.	We will setup Joomla with MySQL Database.
5.	We will setup helm and tiller
6.	Then we will deploy Prometheus and Grafana in the Cluster
7.	Then we will connect the Prometheus(TSDB) with Grafana and export dashboard from Grafana Labs.

For more information, read this tutorial [article](https://medium.com/@dipadityadas/deploying-joomla-mysql-prometheus-grafana-on-amazon-eks-9518b9eae480?source=friends_link&sk=27d043a26d2c2669c1e774964d550e1c) 