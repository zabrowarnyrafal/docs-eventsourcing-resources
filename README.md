# Event Sourcing resources and materials

> List of useful tutorials, libraries and software regarding cqrs, event sourcing, event-driven system, event-driven architecture.

### Table of Contents
- [Github repositories](#github-repositories)
- [Samples](#samples)
- [Articles](#articles)
- [Videos](#videos)

## Github repositories

* https://github.com/volak/Aggregates.NET/tree/master/src/Aggregates.NET.EventStore -c# aggregates, snapshotting, out of band events, competing consumers, conflict resolving
* https://github.com/froko/SimpleDomain - c# aggregates, snapshotting, events versioning, SQL eventstore, GES eventstore, RavenDb eventstore
* https://github.com/NEventStore/NEventStore - c#, not updated
* https://github.com/mfelicio/NDomain - c#, fluent and async api, azure bus, redis message broker, sql eventstore
* https://github.com/Elders/Cronus - c#, microservices, cassandra eventstore, sql eventstore, protobuf, cassandra projections, elasticsearch projections, rabbitmq messaging
* [EventFlow](https://github.com/eventflow/EventFlow) - aggregates, async api, configurable, SQL eventstore, GES eventstore, InMemory eventstore, sqlserver projections, elasticsearch projections, snapshotting, sagas aka process managers, scheduling, policies
* [CQRSLite](https://github.com/gautema/CQRSlite) - net core, uow and repository of aggregates, snapshotting, pluggable, missing implementations
* https://github.com/commanded/commanded - elixir cqrs, Pg eventstore, GES eventstore, sagas, projections, scheduling, missing snapshotting
* [MS Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) - ddd, Azure ready, SQL eventstore, scheduling, snapshotting, authorization layer, projections, Microsoft workers made it
* https://github.com/Chinchilla-Software-Com/CQRS - based on CQRSlite, Azure ready, uow and repository of aggregates, GES eventstore, ASB support, Azure CosmosDb support, MongoDb projections, Akka.net support, authentication layer, sagas, commercial support
* [Cirqus](https://github.com/d60/Cirqus) - ddd, EF projections, MongoDb projections, MongoDb eventstore, SQL eventstore, snapshotting, caching
* [BrighterCommand/Paramore](https://github.com/BrighterCommand) - ports and adapters, Pg eventstore, SQLServer eventstore, SQLite eventstore, MySQL eventstore, ASB support, Kafka support, Redis queues support, RabbitMQ support, policies
* [LiquidProjections](https://github.com/liquidprojections/LiquidProjections) - projector of events, RavenDb projections,NH projections, event types mapper

## Samples

## Articles
* [CQRS in Azure](https://blogs.msdn.microsoft.com/azuredev/2017/03/09/cqrs-in-azure-part-1/) - Microsoft article 'bout using CQRS in Azure (4 parts)
* [Task based UI](http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/) - Greg young explanation of UI patter suitable for ES or distributed storage 

## Videos
* [EventStore as read model](https://skillsmatter.com/skillscasts/3836-event-store-as-a-read-model) - how GES projections is working
* [A deep look into the EventStore](https://vimeo.com/53153270) - GES internals by greg Young
