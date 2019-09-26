Ansible Role Devtools for (MacOS)
=========

A bundle of projects to help developer tools installations.

Requirements
------------

* Homebrew Installation:
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update
brew install python
brew install ansible

# Install pip
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
sudo python get-pip.py
pip install --upgrade pip
pip install regex
```

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
    - hosts: localhost
      roles:
         - { role: ansible-role-devtools-macos}
```

License
-------

BSD

Author Information
------------------
Sammer Valgas - XGH Expert / Devops Specialist
