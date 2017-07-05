#Ansible role for dovecot
##Usage
To run this playbook, you need to set the`dovecot_postmaster` to the email adress of the postmaster for this dovecot instance.
For other variables, have a look in `defaults/main.yml`. By default this role will set up a dovecot that listens on 993 with SSL and on 143 with STARTTLS. To disable this, set the imap/imaps port variable to empty or False.
