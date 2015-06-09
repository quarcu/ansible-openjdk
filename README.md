# OpenJDK Java role for Ansible

Installs OpenJDK Java from the OpenJDK PPA and applies the specified configuration.

Forked from [https://github.com/ssilab/ansible-java](https://github.com/ssilab/ansible-java) and adapted for OpenJDK.

Tested on Ubuntu 14.04 Server.

## Requirements

None.


## Role Variables

	jdk_version: '8'	# Which version of Java to install

## Example Playbook

    - hosts: 'servers'
      roles:
        - role: 'quarcu.openjdk'
          jdk_version: '7'

# License

This playbook is provided 'as-is' under the conditions of the BSD license. No fitness for purpose is guaranteed or implied.
