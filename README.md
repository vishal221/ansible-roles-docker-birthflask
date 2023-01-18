# ansible-roles-docker-birthflask

This project creates below roles:
 - deploy ( Start the containers using docker compose)
 - installDocker (Install docker and docker compose)
 
Commands to create these roles:

  - ansible-galaxy init deploy
  - ansible-galaxy init installDocker
  
Command to run the playbook:
  - ansible-playbook -i inventory.yaml playbook.yaml
