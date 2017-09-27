Role Name
=========

nakahiro386.ansible-bash-completion

Requirements
------------

None.

Role Variables
--------------

```yaml
# defaults file for nakahiro386.ansible-bash-completion
ansible_bash_completion_clone_dir: "/usr/local/src/ansible-completion"
ansible_bash_completion_git_repo: "https://github.com/dysosmus/ansible-completion.git"
ansible_bash_completion_version: "HEAD"
ansible_bash_completion_install_dir: "/etc/bash_completion.d"
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: nakahiro386.ansible-bash-completion
      become: yes
```

License
-------

MIT

