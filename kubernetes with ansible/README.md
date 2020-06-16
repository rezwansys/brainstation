# Kubernetes Cluster using Ansible
ansible-playbook setup_master_node.yml

* Once the master node is ready, run the following command to set up the worker nodes.

ansible-playbook setup_worker_nodes.yml


* Once the workers have joined the cluster, run the following command to check the status of the worker nodes.

kubectl get nodes




