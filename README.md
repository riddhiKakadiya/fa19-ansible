# fa19-ansible

# CSYE 7374 - Fall 2019

## Team Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
| Jai Soni| 001822913|soni.j@husky.neu.edu |
| Riddhi Kakadiya| 001811354 | kamlesh.r@husky.neu.edu |
| Sreerag Mandakathil Sreenath| 001838559| mandakathil.s@husky.neu.edu|
| Vivek Dalal| 001430934 | dalal.vi@husky.neu.edu |

# Technology Stack

# Ansible Playbooks
1. launch-web-server.yaml
2. terminate-web-server.yaml

# Command lo launch server
```bash
ansible-playbook launch-web-server.yaml -e "region=us-east-1 ssh_key=<ec2-keypair-name> ssh_pem_file_location=<ssh_pem_file_location>"  
```
# Command for server termination
```bash
ansible-playbook terminate-web-server.yaml -e "region=us-east-1 key=type value=test_instance"
```

