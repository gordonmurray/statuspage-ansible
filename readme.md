# statuspage-ansible
Playbooks &amp; Tasks to use the Statuspage API with Ansible

To use it, add your Statuspage API key and Page ID to /roles/statuspage/vars/main.yml

Then run ansible-playbook create_incident.yml

The output will show the Statuspage Incident ID