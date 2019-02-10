# PgBouncer

[PgBouncer](https://pgbouncer.github.io/) is a lightweight connection pooler for PostgreSQL.

This chart is inspired by [Future Tech Industries's](https://github.com/futuretechindustriesllc/charts) and adds only a couple of features. If you do not need internal load balancing I would recommend using their repositry as they might have more expertise and maintain it more regularly. 

# Usage

- Password authentication to PgBouncer itself.
- Probes on PgBouncer.
- Ability to inject custom values into PgBouncer.ini
-   The ability to set the listen backlog, and a higher default.
- Guaranteed quality of service on all pods.
