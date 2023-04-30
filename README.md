Playbook: install_bf2_sbx
=========

This Playbook will install the bf2 and bf2 sandbox server on your system.
It also creates the user bf2 on it.
The password for this user to be set will be asked from a prompt.
NOTE: The same password will be set on all Systems!

Requirements
------------

This Playbook requires a user "ansible" to be present on the target system with root privileges.
To Authenticate to all Systems with ansible, a public key is used. The corresponding private key and also its public key are delivered 
in the role "install_sandbox_server". The public key is encrypted using ansible-vault

