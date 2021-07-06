# ansible-linux-users-creation-deletion
ansible playbooks to create and delete  ssh users  

creating ssh keys on localhost:
-------------------------------

ansible-playbook create-ssh-key.yml -vvv

creating a user called 'devops' on localhost as well as on target hosts along wth ssh keys:
----------------------------------------------------------------------------------------

ansible-playbook ssh-user.yml -vvv
