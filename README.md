# nginx_install_guide

first remove nginx
--> sudo apt purge nginx
--> sudo apt autoremove 

remove folders 

cd to 'cd /etc/systemd/system'
and remove  ‘rm nginx.service'  

and reboot

then try   systemctl status application.service , where application here is nginx
