# ansible_repo

If you don't want to pass any arguments to this playbook it has default data available. The command for running this playbook is

ansible-playbook mac_details.yml

If you want to pass any arguments( mac address and authentication key ) use the following command.

ansible-playbook mac_details.yml -e "mac=44:38:39:ff:ef:57 token=dfasdfdsnfHMV79WR3Nv6MThkhaxA9"

Note: Here I have provided the dummy token don't use that token. It is for understanding purpose.
