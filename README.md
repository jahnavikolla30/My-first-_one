# My_first_one.war
#!/bin/bash
yum install httpd git -y
service httpd start
chkconfig httpd on
cd /var/www/html
git clone https://github.com/jahnavikolla30/My-first-_one.git
service httpd restart

