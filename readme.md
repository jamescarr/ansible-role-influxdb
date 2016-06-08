# Ansible Role: InfluxDB

[![Build Status](https://travis-ci.org/jamescarr/ansible-role-influxdb.svg?branch=master)](https://travis-ci.org/jamescarr/ansible-role-influxdb)

Installs InfluxDB on Debian/Ubuntu.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Dependencies

None.

## Example Playbook

    - hosts: utility
      vars_files:
        - vars/main.yml
      roles:
        - jamescarr.influxdb

## License

MIT / BSD

## Author Information

This role was created in 2016 by [James Carr](http://blog.james-carr.org/).
