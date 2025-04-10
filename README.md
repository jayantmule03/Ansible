Installing Ansible on Ubuntu
<br/>
Ubuntu builds are available in a PPA here.
<br/>
To configure the PPA on your system and install Ansible run these commands:
## Installation

To install Ansible, run the following commands:

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
