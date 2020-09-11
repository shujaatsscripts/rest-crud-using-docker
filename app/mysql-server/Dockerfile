FROM mysql/mysql-server:5.7
ENV MYSQL_ROOT_PASSWORD_FILE root
ENV MYSQL_DATABASE test
ENV MYSQL_USER test
ENV MYSQL_PASSWORD test
COPY *.sql /docker-entrypoint-initdb.d/