1. In the hosts file we need to write ip and username destination server
2.In the "deploy_mailcow.yml" file, within the "Generating configure" block, you need to replace "mail.domain.ck.ua" with your own mail domain.
Then we can start ansible-playbook main.yml
