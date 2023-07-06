# Kali + Ubuntu Setup

In this section you will setup a handy connection between your kali and your ubuntu server.

First get the IP addresses for both machines. Note them down somewhere.

## Add server to hosts file in kali
`sudo vim /etc/hosts`

In this file add in the IP address of your ubuntu server. On the right hand side add in the a name you want to give to your server (e.g. pwst-server).
This will be used then to connect to your server and using the name instead of the IP address.

Example: `ssh ubuntu@pwst-server`