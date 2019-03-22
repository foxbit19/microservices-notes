# Technology scouting

<!-- vscode-markdown-toc -->
* [Kafka](#Kafka)
	* [Resources](#Resources)
* [Zookeper](#Zookeper)
	* [Resources](#Resources-1)
* [Protobuf](#Protobuf)
	* [Resources](#Resources-1)
* [Axon](#Axon)
* [GraphQL](#GraphQL)
	* [Resources](#Resources-1)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

This document provides some (brief) descriptions about useful technologies for microservices implementation.

## <a name='Kafka'></a>Kafka

Apache Kafka is a community distributed event streaming platform capable of handling trillions of events a day. Initially conceived as a messaging queue, Kafka is based on an abstraction of a distributed commit log.

<img width="500px" src="img/kafka-apis.png" />

> This kind of technology is important in order to implement an event sourcing service.

### <a name='Resources'></a>Resources

- [Official documentation](https://kafka.apache.org/)

## <a name='Zookeper'></a>Zookeper

ZooKeeper is a distributed, open-source coordination service for distributed applications. It exposes a simple set of primitives that distributed applications can build upon to implement higher level services for synchronization, configuration maintenance, and groups and naming. It is designed to be easy to program to, and uses a data model styled after the familiar directory tree structure of file systems.

<img width="500px" src="img/zkservice.jpg" />

> This service is useful as a base for a microservices architecture. It handles some of main issues on coordination services implementation.

### <a name='Resources-1'></a>Resources

- [Official documentation](https://zookeeper.apache.org/doc/current/zookeeperOver.html)

## <a name='Protobuf'></a>Protobuf

Protobuf is a language-neutral, platform-neutral, extensible way of serializing structured data for use in communications protocols, data storage, and more.

> 

### <a name='Resources-1'></a>Resources

- [Official repository](https://github.com/protocolbuffers/protobuf)
- [Developer guide](https://developers.google.com/protocol-buffers/docs/overview)

## <a name='Axon'></a>Axon

Axon is a framework and server for event-driven microservices.

### References

[Reference guide](https://docs.axoniq.io/reference-guide/)

## <a name='GraphQL'></a>GraphQL

GraphQL is a query language for your API, and a server-side runtime for executing queries by using a type system you define for your data.

<img width="700px" src="img/graphql-example.png" />

> In the microservices context, this kind of technology is useful because it acts as a public API gateway, masquerading services API from public access.

### <a name='Resources-1'></a>Resources

- [Official documentation](https://graphql.github.io/learn/)


