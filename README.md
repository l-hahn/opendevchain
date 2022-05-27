# cloud-environments-example

This repository contains an example environment structure to demonstrate, how the OpenDevChain Cloud repositories can be used.
For each relevant application there is one playbook provided; with 

$ ansible-playbook <target-playbook>.yml

you should be able to execute and example playbook.

Please make shure, that at least URLs/DNS entries are correct, or remove the "letsencrypt: true" attribute from website configurations; otherwise runs will fail as letsencrypt is probably not correctly configured to resolve DNS to your server.

The initial roles are kept in this repository; for newer versions of Ansible Roles, please have a look at:

https://git.opendevchain.de/OpenDevChain


For any questions, please do not hesitate to reach out to me:

info@opendevchain.de

Regards
