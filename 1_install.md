
## Install Certbot and Nginx on RHEL (AWS)


```
yum-config-manager --enable rhui-REGION-rhel-server-optional
yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
yum install -y certbot nginx
```
