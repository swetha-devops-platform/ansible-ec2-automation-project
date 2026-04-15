# Project Title  - “Automating Multi-OS EC2 Provisioning with Conditional Configuration using Ansible”

# Project Description

- Designed and implemented an end-to-end automation solution using Ansible to provision and manage AWS EC2 instances.

- The project focuses on dynamic resource creation using loops, secure access configuration, and intelligent task execution using conditionals based on system facts.

# Project Overview

This project demonstrates real-time DevOps automation where I used Ansible to:

- Provision multiple EC2 instances (Ubuntu & CentOS) using loops

- Configure passwordless SSH authentication between control node and target instances

- Apply conditional logic (when) to automate selective operations

- Perform OS-based task execution using Ansible facts


# Key Implementations

**Task 1: EC2 Provisioning using Loops**

Created 3 EC2 instances dynamically

  - 2 Ubuntu instances
  - 1 CentOS instance
  - Used Ansible loop to avoid repetitive code


**Task 2: Passwordless Authentication**

- Generated SSH key pair on control node

- Copied public key to all EC2 instances

- Enabled seamless communication without manual password entry


**Task 3: Conditional Automation**

- Applied condition: when: ansible_os_family == "Debian"

- Shutdown executed only on Ubuntu instances
  

# Tools & Technologies Used

- Ansible
  
- AWS EC2
  
- YAML
  
- SSH

  
# What I Learned

- Writing efficient automation using loops

- Making smart decisions using conditions (when)

- Handling real-time infrastructure scenarios

- Importance of idempotency and dynamic execution
