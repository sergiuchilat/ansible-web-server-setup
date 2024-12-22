# Ansible web server setup

This repository contains the following ansible playbooks:
- Configure server
  -  Set Timezone
- Install Nginx
- Install Docker & Docker Compose
- Create GitHub User for deployment of applications from GitHub

> Multiple environments (dev, staging, production) with different configurations are supported

# One time initial setup

### Config server

```bash
ansible-playbook ./playbooks/configure-server.yml 
```

### Install Nginx

```bash
ansible-playbook ./playbooks/install-nginx.yml
```

### Install Docker and Docker Compose

```bash
ansible-playbook ./playbooks/install-docker.yml
```

### Create APP User

```bash
ansible-playbook ./playbooks/create-app-user.yml
```

### Create GitHub User
    
```bash
ansible-playbook ./playbooks/create-github-user.yml
```

