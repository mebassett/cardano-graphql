FROM hasura/graphql-engine:v1.2.1.cli-migrations-v2
RUN mkdir -p /tmp/hasura-project
COPY ./migrations /tmp/hasura-project/migrations
COPY ./metadata /tmp/hasura-project/metadata
COPY ./docker-entrypoint.sh /bin/