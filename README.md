Ansible bootstrap line
======================

Usage:
Before any other playbook insert this line:
- include: roles/bootstrap/init.yml

It will place python on target if it does not exist. Currently suports only debian/ubuntu.
