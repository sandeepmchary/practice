# the url is used for reference
#https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04

# sudo apt-get install
# sudo apt-get install apache2
# sudo systemctl restart apache2
# sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
# sudo systemctl restart apache2
# create file at /var/www/html/info.php 
content of the file are 
<?php
phpinfo();
?>

For centos

# sudo yum install httpd
# sudo systemctl start httpd
# sudo yum install php libapache2-mod-php php-mcrypt php-mysql
# sudo systemctl restart httpd
