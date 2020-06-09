# AWX Example

    2020 Ondrej Sika <ondrej@ondrejsika.com>

## Deploy

```
terraform init
terraform apply
git clone -b 11.2.0 https://github.com/ansible/awx.git
ansible-playbook setup.yml
ansible-playbook awx/installer/install.yml
```
