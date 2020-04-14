node_exporter
=========

this role will install prometheus node_exporter as a service on your servers supports any systemd distrubution.

Requirements
------------

--

Role Variables
--------------

- prometheus.config.node.version: 0.18.1
- prometheus.config.node.listen: will automaticaly set to fist private network ip address
- prometheus.config.node.port: 9100
- prometheus.config.node.path: /metrics
- prometheus.config.node.max_requests: 0

Dependencies
------------

--

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - node_exporter

License
-------

GPL-v3

Author Information
------------------

Arash Haghighat
