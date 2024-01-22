FROM postgres:latest

RUN apt-get update
RUN apt-get -y install locales-all

ENV LANG ja_JP.UTF-8

RUN apt -y update

# 外部からのアクセスを可能に変更
# RUN sed -i -e "/#listen_addresses = 'localhost'/c listen_addresses = '*'" /var/lib/postgresql/data/postgresql.conf
# RUN sed -i -e "s/trust\$/md5/g" /var/lib/postgresql/data/pg_hba.conf
