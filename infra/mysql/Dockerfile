FROM mysql:8.0

ENV MYSQL_DATABASE=${DB_NAME:-kredo_laravel} \
  MYSQL_USER=${DB_USER:-kredo} \
  MYSQL_PASSWORD=${DB_PASS:-password} \
  MYSQL_ROOT_PASSWORD=${DB_PASS:-password} \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf
