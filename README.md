# Proglog

Proglog is a learning project based on the book *Distributed Systems in Go*.
The goal is to implement a distributed append-only log while exploring
core distributed systems concepts in a hands-on way.

## Learning Goals

- Append-only logs as a foundational primitive
- Replication and ordering
- Consensus
- Failure modes and recovery
- Idiomatic Go concurrency patterns

## Running

I'm using Go 1.25. The book requires 1.13+

```bash
go run ./cmd/server