FROM httpd:2.4

ENV PORT=8080

COPY /src/index.html /usr/local/apache2/htdocs/

EXPOSE $PORT

CMD ["httpd", "-D", "FOREGROUND"]
