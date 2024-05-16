# hive-metastore

This repo contains:

- the Dockerfile and associated scripts to build the `hive-metastore` docker image.
- A corresponding helm chart.

A postgresql server with an empty database is to be provided. An init job will take care of creating the DB schema.

Also, access to the target S3 service is required.

Just type `make` to display possible targets

