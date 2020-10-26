
# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-nginx

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----


# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-nginx

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----


# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-nginx

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----


# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-nginx

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----

nginx
======

Install latest nginx on centos.

Requirements
------------

none

Role Variables
--------------

- `nginx_dir` - Path on host where nginx will keep it's data, default to `/srv/nginx`
- `nginx_config` - Name of the template to use for config
- `nginx_ssl_certificate_path` - Local path to an ssl certificate and key,
  .crt and .key will be appended to the path for the certificate and key respectively.

Dependencies
------------

none

Example Playbook
----------------


    - hosts: servers
      roles:
      - role: nginx
        nginx_config: mynginxconfig.j2
        nginx_ssl_certificate_path: /secret/myserver



License
-------

MIT

