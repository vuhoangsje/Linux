# Here are some guide
# install nginx: sudo pacman -S nginx
# Test nginx by: sudo systemctl status nginx
# Start nginx: sudo systemctl start nginx
# Caution: do not enable nginx anonymous can install your files
# sudo mkdir /usr/share/nginx/autoindex && chmod 777 -R /usr/share/nginx/autoindex
# Config at this line
# location /{
#            root   /usr/share/nginx/html;
 #           index  index.html index.htm;
  #      }

# To
# location /{
#            root /usr/share/nginx/autoindex;
#            autoindex on;
# }

# Reload nginx: sudo systemctl reload nginx
# Check nginx status again by: sudo systemctl status nginx