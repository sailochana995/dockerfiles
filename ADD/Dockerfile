FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/sailochana995/dockerfiles/blob/main/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html 
CMD  ["nginx", "-g", "daemon off;"]



