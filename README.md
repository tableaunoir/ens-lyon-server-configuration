# ens-lyon-server-configuration

 This repository contains information about the configuration of the tableaunoir server at ENS Lyon.
 
 
# Location of the certicates
/etc/letsencrypt/live/tableaunoir.ens-lyon.fr/fullchain.pem
/etc/letsencrypt/live/tableaunoir.ens-lyon.fr/privkey.pem

# Modify the configuration of nginx

        nano /etc/nginx/nginx.conf

# Run nginx
In order to run nginx:

        systemctl start nginx
        systemctl restart nginx
        systemctl status nginx

