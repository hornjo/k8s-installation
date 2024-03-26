k8s-installation
=========

Installs a high available k8s cluster with with the option to define a load balancer in front of it.

Requirements
------------

- Kubernetes.core collection
- ansible.posix collection

Role Variables
--------------

Dependencies
------------
dnspython

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

