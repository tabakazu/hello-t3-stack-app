FROM node:22.9

WORKDIR /myapp

RUN apt-get update -qq && \
    apt-get install -y postgresql-client

USER node

CMD ["sleep", "infinity"]