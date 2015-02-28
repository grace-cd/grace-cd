# Grace CD

Continuous Delivery with grace.

## Must have / Goals

- `Pipeline => Stage => Job` data model including materials and artifacts
- File-driven config vs database-driven config
- Simple config file format (YML?) and backed by GIT
- Everything on its place:
  - scheduling and synchronization with etcd
  - log aggregation with (graylog/logstash)
  - search with elasticsearch
- Everything is optional, batteries includes
  - provide build-in stages for testing (like `noop`, `fail`) and config
    replacement (`wait for`)
- Security as a requirement
- Written in golang

## Good to have (a.k.a Enterprise Edition)
- Authentication and Authorization
- LDAP support for authentication
- DB driven config
- Audting
- SVN support
- Github PR integration