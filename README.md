# avinetworks.docker

[![Build Status](https://travis-ci.org/avinetworks/ansible-role-docker.svg?branch=master)](https://travis-ci.org/avinetworks/ansible-role-docker)

This role provides the following:
* Installation of Docker following Docker-Engine install procedures as documented by Docker.
* It will manage kernel versions as well, verifying the that the correct kernel for Docker support is installed.

Supports the following Operating Systems:
* CentOS 7
* OracleLinux 7
* Ubuntu 12.04
* Ubuntu 14.04
* Ubuntu 16.04

## Requirements

This role requires Ansible 1.9.3 or higher. Requirements are listed in the metadata file.

## Example Playbook

Install docker to your machine.

    - hosts: servers
      roles:
         - role: avinetworks.docker

## License

BSD

## Author Information

Eric Anderson
