# Hostname role

## Summary

Ansible role that configures the hostname on a Linux server.

## Usage

```yaml
  - role {
    name: hostname:1.0,
    private_hostname: 'bigblue'
    }
```

## Options

- add_to_hosts: static host definition added in /etc/hosts
  - ip
  - fqdn
  - shortname
- private_hostname
