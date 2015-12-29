{{cookiecutter.project_name}}
=======

#### Table of Contents

1. [Overview - What is the {{cookiecutter.project_name}} module?](#overview)
2. [Module Description - What does the module do?](#module-description)
3. [Setup - The basics of getting started with {{cookiecutter.project_name}}](#setup)
4. [Implementation - An under-the-hood peek at what the module is doing](#implementation)
5. [Limitations - OS compatibility, etc.](#limitations)
6. [Development - Guide for contributing to the module](#development)
7. [Contributors - Those with commits](#contributors)

Overview
--------

The {{cookiecutter.project_name}} module is a part of [OpenStack-infra](https://git.openstack.org/cgit/openstack-infra), an effort by the OpenStack infrastructure team to provide continuous integration testing and code review for OpenStack-infra projects.

Module Description
------------------

The {{cookiecutter.project_name}} module is a thorough attempt to make Puppet capable of managing the entirety of {{cookiecutter.project_name}}.  This includes manifests to provision the expected features of this module.  Types are shipped as part of the {{cookiecutter.project_name}} module to assist in manipulation of configuration files.

Setup
-----

### Installing {{cookiecutter.project_name}}

    {{cookiecutter.project_name}} is not currently in Puppet Forge, but is anticipated to be added soon.  Once that happens, you'll be able to install {{cookiecutter.project_name}} with:
    puppet module install openstack-infra/{{cookiecutter.project_name}}

### Beginning with {{cookiecutter.project_name}}

To utilize the {{cookiecutter.project_name}} module's functionality please check the README.

Implementation
--------------

### {{cookiecutter.project_name}}

{{cookiecutter.project_name}} is a combination of Puppet manifests to delivery configuration and extra functionality through types and providers.

Beaker-Rspec
------------

This module has beaker-rspec tests

To run the tests on the default vagrant node:

```shell
bundle install
bundle exec rake acceptance
```

For more information on writing and running beaker-rspec tests visit the documentation:

* https://github.com/puppetlabs/beaker/wiki/How-to-Write-a-Beaker-Test-for-a-Module

Development
-----------

Developer documentation for the entire puppet-infra project.

* http://docs.openstack.org/infra/system-config/puppet.html
