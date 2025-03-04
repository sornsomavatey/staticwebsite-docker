FROM nginx:latest

# Remove default Nginx content
RUN rm -rf /usr/share/nginx/html/*

# Copy the Groovin folder content to Nginx's web directory
COPY Groovin /usr/share/nginx/html

# Expose port 80
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
