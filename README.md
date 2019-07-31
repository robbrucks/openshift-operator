# openshift-operator

## Installing the operator framework on openshift

### Enable Operator Lifecycle Manager

        [OSEv3:vars]
        openshift_enable_olm=true

### Cd into the openshift ansible directory

        cd /usr/share/ansible/openshift-ansible

### Run the playbook to install OLM

        ansible-playbook -i <inventory> playbooks/olm/config.yml


