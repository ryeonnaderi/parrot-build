** Make sure to pip install ansible, apt has an older copy **

# Instructions
* Start with ParrotOS Security
* Install Ansible (sudo pip3 install ansible --break-system-package)
* Clone and enter the repo (git clone)
* ansible-galaxy install -r requirements.yml
* Make sure we have a sudo token (sudo whoami)
* ansible-playbook main.yml


# Run BloodHound
* start neo4j console (sudo neo4j console)
* go to the given url thats in the console
* enter default creds (neo4j)
* enter new password 
* new creds(neo4j:"New Password")
* open new temrinal run (bloodhound)
* enter creds (neo4j:"New Password")
