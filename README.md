## Ansible Playbooks
## Prerequisites

Before you start using the playbooks in this repository, ensure you have the following installed:

- *Ansible*: Version 2.9 or later
- *Python*: Version 3.x
- *SSH Access*: Ensure you have SSH access to your target hosts

## Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/ansible-playbooks.git
cd ansible-playbooks

## Before Run Playbooks
ansible-galaxy collection install ansible.posix
ansible-galaxy collection install community.general
ansible-galaxy collection install community.crypto

## Command to Run Playbook
ansible-playbook XXX.yml
