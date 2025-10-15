# Use lightweight web server
FROM nginx:alpine

# Copy static files
COPY . /usr/share/nginx/html/

# Copy custom nginx config
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]