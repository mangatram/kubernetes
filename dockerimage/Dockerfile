# Use the official Nginx image as a base
FROM nginx:latest

# Remove the default Nginx HTML file
RUN rm /usr/share/nginx/html/index.html

# Copy the custom HTML file to the Nginx HTML directory
COPY ./index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80
