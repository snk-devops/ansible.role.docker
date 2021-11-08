# Docker role for Ansible

Install and configure docker and docker-compose for CentOS/Debian

## Changelog

### v1.5.0

- Split SDK installation vars. Now `docker_sdk` setup only docker in python. 
Variable `docker_compose_sdk` install `dokcer-compose` in python
- Added log shrink settings in docker config