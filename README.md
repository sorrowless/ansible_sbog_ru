sbog/sbog_ru
============

Role to install personal website

#### Requirements

Ansible 2.4

#### Role Variables

```yaml
site_hostname: <site hostname>
origin_remote: <repo with site content>
tls_path: /etc/ssl_certs
```

#### Dependencies

None

#### Example Playbook

```yaml
- name: Deploy personal site to target host
  hosts: sbog_ru_webservers
  remote_user: root

  roles:
    - sbog_ru
```

#### License

Apache 2.0

#### Author Information

Stanislaw Bogatkin (https://sbog.ru)
