# Ansible role 'ansible-role-pcp'

An Ansible role for setting up PCP on any Redhat Family host. In addition, allowing for an assigned host
to be used as a statistics aggregator with focus on grafana.

## Requirements
Either of:
- RHEL 7.4 or later
- CentOS 7.4 or later
- Fedora (29 is the only tested)

## Role Variables
| Variable		| Default		| Comments (type) |
| :---			| :---			| :---		  |

## Dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: ansible-role-pcp
```

## Testing


## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
