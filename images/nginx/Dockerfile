FROM nginx:1.19.8-alpine
 
# ARG SERVER_NAME_MAIN

COPY sites/ /etc/nginx/conf.d/

COPY includes/ /etc/nginx/generic_conf/

COPY nginx.conf /etc/nginx


# RUN sed -i "s/__SERVER_NAME_MAIN__/${SERVER_NAME_MAIN}/g" /etc/nginx/conf.d/main.conf