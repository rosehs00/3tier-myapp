# Use the official Nginx image from the Docker Hub
FROM nginx:alpine

# Copy custom Nginx configuration file
COPY default.conf /etc/nginx/conf.d/

# Copy frontend static files (assuming you have built your frontend project)
# If you have a build step for your frontend, include it here
# For example, for a React project:
# COPY build/ /usr/share/nginx/html
COPY index.html /usr/share/nginx/html

# Expose port 80
EXPOSE 80
