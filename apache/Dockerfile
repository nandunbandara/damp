FROM httpd:2.4.33-alpine
RUN apk update; \
    apk upgrade;

COPY damp.apache.conf /usr/local/apache2/conf/damp.apache.conf
RUN echo "Include /usr/local/apache2/conf/damp.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf