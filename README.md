# VSCode-user-config-Role

[![AlmaLinux9-CI](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/almalinux9-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/almalinux9-ci-caller.yml) [![Rocky9-CI](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/rocky9-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/rocky9-ci-caller.yml) [![CentOSStream9-CI](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/centosstream9-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/centosstream9-ci-caller.yml) [![Fedora43-CI](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/fedora43-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/fedora43-ci-caller.yml)<br>
[![Ubuntu2404-CI](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/ubuntu2404-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/ubuntu2404-ci-caller.yml) [![Debian13-CI](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/debian13-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-vscode-user-config/actions/workflows/debian13-ci-caller.yml)

Role description

This role includes a vagrant based molecule testing setup as a submodule at `molecule/`

## Structure

```code
📦 ansible-vscode-user-config
 ┣ 📂 defaults
 ┃ ┗ 📜 main.yml
 ┣ 📂 meta
 ┃ ┗ 📜 main.yml
 ┣ 📂 molecule
 ┃ ┗ 📂 default
 ┃   ┗ 📜, 📜, 📜, scenario_files
 ┣ 📂 tasks
 ┃ ┣ 📜 absent.yml
 ┃ ┣ 📜 extensions.yml
 ┃ ┣ 📜 main.yml
 ┃ ┣ 📜 present.yml
 ┃ ┣ 📜 settings.yml
 ┃ ┗ 📜 tests.yml
 ┣ 📂 vars
 ┃ ┗ 📜 main.yml
 ┗ 🗒️ README.md
 ┗ 📓 requirements.yml

```

Describe and explain role structure.

## Requirements

Elaborate external dependencies and how to use them.

## Role Variables

* defaults/main.yml
  * first_var
  * sec_var
  * third_var
* vars/main.yml
  * first_var
  * sec_var
  * third_var

## Dependencies

List role ansible-galaxy dependencies - if any.

## Example Playbook

Add an example playbook

```yaml
---

tasks:
  - name: Include ansible-vscode-user-config present
    ansible.builtin.include_role:
      name: ansible-vscode-user-config
    vars:
      state: present

...
```

## License

Add license - if any.
