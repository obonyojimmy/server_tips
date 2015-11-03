# server_tips

JUST SERVER TIPS 

 web-admin server crash fix 
 

To fix that, you can try the following:

Stop webmin with: /etc/init.d/webmin stop

Look for a running Webmin process: ps auxw | grep miniserv | grep webmin

Use the "kill" command to kill any processes you find

Start up Webmin with: /etc/init.d/webmin start

After doing that, does it start up for you?

-------------
php composer.phar require phois/whois --working-dir=/var/www/html2/laravel

