# Ansible Nginx Installer for RHEL

This project installs and starts the Nginx web server on a Red Hat-based EC2 instance using Ansible.

## 🔧 Tech Stack
- Ansible
- EC2 (RHEL / CentOS / Amazon Linux)
- SSH (via `.pem` file)

## 🚀 Usage

```bash
ansible-playbook -i ansible/inventory.ini playbook.yml
