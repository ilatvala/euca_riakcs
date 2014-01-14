This ansible playbook will make a ciak-cs installation from 5 eucalyptus Centos 6 instances.
Ephemeral disk will be used for storage.
Remember to run "export ANSIBLE_HOST_KEY_CHECKING=False", if you have existing instance keys.
Source your eucalyptus credentials before running the script.

Usage: ansible-playbook --private-key=yourprivatekey euca_riakcs.yml

s3 URL, access key and secret key will be printed to the screen at the end of the playbook.

