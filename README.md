Apimon-executor
=========

Provision apimon-executor component.

Requirements
------------


Role Variables
--------------

TODO
- variables for executor host provisioning:
- variables for executor installation:
  - clouds_yaml_content
  - executor_image
  - executor_config_content

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Provision Executor
      hosts: executor
      serial: 1
      roles:
        - opentelekomcloud_infra.apimon_executor
      tags: executor

License
-------

Apache 2.0

Author Information
------------------

OpenTelekomCloud.
