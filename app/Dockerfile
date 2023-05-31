FROM python:3.6-alpine
LABEL maintainer.email="ulrich@eazy.com"
WORKDIR /opt
RUN pip install flask
EXPOSE 8080
ENV ODOO_URL=http://odoo.com  PGADMIN_URL=http://pgadmin.org
COPY . /opt
ENTRYPOINT python app.py