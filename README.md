# Server configuration project

* IP address: 34.214.184.149
* ssh port: 2200
* url: 34.214.184.149/kittycat
* ssh key for a grader: nopassphrase
* resource: digital ocean tutorial (https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)


## Summary:

This ubuntu server is configured to run an catalog app using flask through mod_wsgi in apache2.
The ssh port number was changed to 2200 from default 20, and remote root user login is disabled.
grader has sudo access.
Firewall is configured to only allow for ssh, http, and ntp.
users are required to authenticate using RSA keys.
The catalog lets you create a catalog of cats and their items using google+ sign in. The app uses
postgresql database server.

## Notes to reviewer:
The ssh key is contained in the ssh folder.
