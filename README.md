# ClickHouse cluster cluster_1S_3R

A ClickHouse cluster with 
- 3 dedicated ClickHouse Keepers
- 1 shard with replication across 3 Clickhouse VMs

Use this for:
- BYOA
- Integrating with other services
- Ephemeral environments
- Customizing Clickhouse deployments

This spec file deploys a configuration very similar to [this
example in the documentation](https://clickhouse.com/docs/en/architecture/replication) except sharded over 3 ClickHouse VMs.
See the docs for information on terminology, configuration, and testing.
See the [Chproxy docs](https://www.chproxy.org/) for information on the proxy.
