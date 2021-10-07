FROM mysql:5.7

# copy the base sql file
# COPY base.sql /docker-entrypoint-initdb.d/base.sql

RUN /etc/init.d/mysql start
CMD ["sh", "-c", "tail -f /dev/null"]