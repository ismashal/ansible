#Ansible role for AWS cloud watch agent and SSM agent

- Install Ansible on ec2 instances as controller 
- Checkout the current repo in /etc/ansible
- Add/update the inventory in  /etc/ansible/hosts file as per the group. Eg. IP of node and private_key.pem file path
- Create an [IAM instance profile to use with SSM Agent](https://docs.aws.amazon.com/systems-manager/latest/userguide/setup-instance-profile.html). Ignore if you already created for account.
- Execute the command ``` ansible-playbook playbook.yml ```

