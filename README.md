# Ansible Role: Oracle Linux 8.x STIG Hardening

Based off Oracle Linux 8 V2R7 from the DoD Cyber Exchange

## Usage

Install the required collections:

```bash
ansible-galaxy collection install -r collections/requirements.yml
```

Run the role locally:

```bash
ansible-playbook -i localhost, -c local site.yml
```

Run the role against hosts in an inventory:

```bash
ansible-playbook -i inventory.yml site.yml
```
