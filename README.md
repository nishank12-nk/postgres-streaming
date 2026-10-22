# Task 2 - PostgreSQL Streaming Replication

PostgreSQL 16 Primary -> Standby streaming replication using two Docker containers.

- `docker-compose.yml` starts `pg-primary` (port 5433) and `pg-standby` (port 5434) on the Docker network `pgnet`
- `config/primary/` has `postgresql.conf` and `pg_hba.conf` of the Primary
- `config/standby/` has the Standby configuration files

Lab setup only. The passwords in this repository are for local testing.
