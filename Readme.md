----------------------------Devops Project-------------

-->In this project i was provisioned all the servers on #awscloud  using IAAC tool(terraform)

--> Configured DevOps tool chain with the tools git (VCS), github (SCM), Maven(Buildtool), jenkins(CI/CD tool),nexus (Software Repository) Ansible(Configuration Managment tool) ,tomcat and docker (to host web application).

--> I was written Ansible playbooks in Ansible Control Node to Download the latest build artificat from Nexus and to Deploy on Ansible-Managed Nodes (tomcat and docker) 

-->To automate all these process i was written Jenkinsfile with following stages

1-Build

2-unit test

3-Deploy-to-Nexus

4-Deploy-to-tomcat

5-Deploy-to-Docker
"# devops" 
