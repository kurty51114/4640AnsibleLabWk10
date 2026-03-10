# 4640AnsibleLabWk10
## 1. Making Playbook.yml
- Create a new file named playbook.yml based on play.yml

## 2. Create Modular Roles
- Create frontend and redis roles
- Move all tasks, variables, and logic into the tasks/main.yml of each role

## 3. Moving files
- Move your supporting files to the right places

## 4. Make Handlers
- Define a handler in roles/frontend/handlers/main.yml to restart or reload Nginx
- Use the notify keyword

## 5. Run file
ansible-playbook -i inventory_aws_ec2.yml playbook.yml
