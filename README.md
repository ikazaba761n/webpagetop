# webpagetop
codespace web page

sudo apachectl -k start
ps -ax | grep apache
   2557 ?        Ss     0:00 /usr/sbin/apache2 -k start
   2560 ?        Sl     0:00 /usr/sbin/apache2 -k start
   2561 ?        Sl     0:00 /usr/sbin/apache2 -k start
   4321 pts/0    S+     0:00 grep --color=auto apache
   

port add

webpage improved-************************-80.app.github.dev/
top gdata.png
ok


sudo systemctl status apache2

"systemd" is not running in this container due to its overhead.
Use the "service" command to start services instead. e.g.: 

service --status-all

