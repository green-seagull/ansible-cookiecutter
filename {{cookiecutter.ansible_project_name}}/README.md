# {{cookiecutter.ansible_project_name}}
{{cookiecutter.ansible_project_description}}

## Quickstart
1. To test playbook locally:
  ```
  ansible-playbook test-role.yml
  ```
{% if cookiecutter.show_license != 'False' %}  
## License
[GPLv3](LICENSE)
{% endif %}