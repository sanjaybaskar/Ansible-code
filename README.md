# Ansible-code

Webserver group
Tasks
    Play1:Install httpd
    Properties:
        -> package name
        -> package state
    Play2:Start httpd services
    Properties:
        -> service name 
        -> service state 
    Play3:Copy index.html file to /var/www/html
    Properties:
        -> src
        -> dest