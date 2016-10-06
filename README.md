ansible-composer for Debian/Ubuntu
============

Ansible role for installing [composer](https://getcomposer.org) on the system.

## Overwrite Default Variables

The `vars/main.yml` file should contain your list of packages you want to install in order to override defaults found in `defaults/main.yml`.

```yml
---
install_to_path: /usr/local/bin
```

Feel free to change the installation path for the `composer.phar`.
