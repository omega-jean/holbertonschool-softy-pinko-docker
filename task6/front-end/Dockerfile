# Use the latest version of nginx
FROM nginx:latest

# Copy the front-end files to the nginx html directory
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the nginx config file to the proper location
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

# Expose port 9000
EXPOSE 9000
