
<!-- THIS IS A GENERATED FILE, DO NOT EDIT -->

Assemble your own custom cloud! This role provisions virtualization, administration and monitoring solutions. Check the usage section for the exhaustive list of components.
 Version 0.1.


## Supported Platforms

  * Ubuntu
  * Debian

## Variables

| Name | Value | Description |
|------|-------|-------------|
| `cloudkit_docker_address` | _default_ `0.0.0.0` |  |
| `cloudkit_docker_autostart` | _default_ `True` |  |
| `cloudkit_docker_installer_path` | _var_ `/var/tmp/install_docker.sh` |  |
| `cloudkit_docker_port` | _default_ `8090` |  |
| `cloudkit_docker_state` | _default_ `ignored` |  |
| `cloudkit_environment` | _default_ `{}` | Common environment variables, such as http_proxy |
| `cloudkit_webvirtmgr_state` | _default_ `ignored` |  |



## Usage

To use this role from a **playbook**, 
register its ID in the project `requirements.{txt,yml}` file.
To add this role as another **role dependency**,
register its ID in the `dependencies` list of the role manifest `meta/main.yml`.
For further details,
please refer to the Ansible documentation at https://docs.ansible.com/playbooks_roles.html.

By default, this role does nothing as all `*_state` variables are set to `ignored`.
For the components you're interested in, set the `*_state` variables to `present` or `absent.



## Maintenance

Install [ansible-universe](https://github.com/fclaerho/ansible-universe)
and run `ansible-universe check` to re-generate this distribution.

The following files are generated or updated based on various role assets:
  * tasks/main.yml
  * README.md


