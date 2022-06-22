FROM linsay1999/yelb-app:postgres-10.0
MAINTAINER Guy Alfred

WORKDIR /

COPY init-yelb-db.sh /docker-entrypoint-initdb.d/init-yelb-db.sh

ENV POSTGRES_PASSWORD=postgres_password
