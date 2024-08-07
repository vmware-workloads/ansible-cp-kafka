# ansible-cp-kafka

## Description
This is an Ansible Automation Platform playbook to deploy Confluent Platform v7.6.1 using VM deployed by VMWare Aria Automation. It was designed to work in conjunction with our sample Aria Assembler Blueprint.

This playbook was created for demonstration purposes and should serve as a basis to create a more comprehensive playbook. 

**Note**: This playbook leverages the _confluent.platform_ collection published by Conluent on Ansible Galaxy. This playbook is imported in the _./collections/requirements.yml_ file.

## Playbook Structure

```
ansible-crdb
├── collections
│   └── requirements.yml
├── roles
│   ├── ansible_role_create_hosts_file
│   │   └── ...
│   └── ansible_role_mount_broker_disks
│       └── ...
├── deploy.yml
├── LICENSE
└── README.md
```

- `collections/`: directory containing the module requirements for the playbook.
- `roles/`: directory containing the roles.
- `deploy.yml`: the playbook file.
- `LICENSE`: project license.
- `README.md`: instructions and links related to this playbook.

