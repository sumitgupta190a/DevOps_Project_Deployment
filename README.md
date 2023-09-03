# DevOps_Project_Deployment

• End to End Project for DevOps Resume
- Built Kubernetes Cluster on AWS from Scratch with Minukube
- Setup and Managed Docker Containers for Django and React Applications into Kubernetes Pods.
- Managed Deployment, Replication, Autohealing, and auto scaling for Kubernetes Cluster.
- Managed network the service with host IP allocation through a proxy on aws ec2 and route53

..........Commands to run this project...........
#cd ymlfile
#kubectl apply -f pod_1.yml
#kubectl apply -f deployment_1.yml
#kubectl apply -f service_1.yml

..........TO GIVE THE NAME OF OUR IP..........
#sudo vim /etc/hosts (In this file write the ip and name that you want to give)
Ex- 192.168.59.3 todo-app.com (but this work in the private network)

..............TO CHECK THAT URL...........
#curl -L todo-app.com:Port_No
