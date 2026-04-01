Initialize k8s cluster operating in Linux (Ubuntu or RHEL)

STEP
1. Set up hosts.ini
2. Please modify the file in Kubernetes version set ./roles/common/vars/main.yml
3. run ansible "ansible-playbook -i hosts.ini site.yml"