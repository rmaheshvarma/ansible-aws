Using this ansible script we can create 
 1. One VPC
 2. Two Public Subnets
 3. Two Private Subnets
 4. Create the IneternetGateway
 5. Creating Public Routing table and Private Routing table


In public routing table we have associated the public subnets
In Private routing we have associated the private subnets

Note:

As of now I have created this playbook without variables. Very soon I would modify this play book as per best practice.



How to execute this ansible Script

From Ansible controll machine

 $ ansible-playbook site.yml

Since I have written role for this playbook, we can execute like that. 


