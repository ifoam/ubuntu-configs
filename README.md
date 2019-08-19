# ubuntu-configs
These are code snippets used to configure Ubuntu


#Enable FQDN in syslogs for Ubuntu 18.04

**vi /etc/hosts**

Add FQDN:
>127.0.0.1 hostname.domain.com

**vi /etc/rsyslog.conf**

Add: 
>$PreserveFQDN on

**Restart rsyslog:**
>service rsyslog restart
