# Getting Started Guides

This repository contains a set of examples about the Quarkus framework.

See [CONTRIBUTING](CONTRIBUTING.md) for how to build these examples:

* [Getting Started](./getting-started): Application creation, Rest endpoint, Dependency Injection, Test, Packaging
* [Getting Started - Async](./getting-started-async): Illustrate how to use `CompletionStage` to handle asynchronous actions
* [Getting Started - Native](./getting-started-native): Packaging of the application into a native executable
* [Getting Started - Kubernetes/OpenShift via Dockerfile](./getting-started-kubernetes): Deployment of the application to Kubernetes and/or OpenShift
* [Getting Startied - OpenShift S2I](./getting-started-openshift-s2i): Deployment of the application to OpenShift with S2I
* [Getting Started - Knative](./getting-started-knative): Deployment of the Knative service to Kubernetes and/or OpenShift
* [Application Configuration](./application-configuration): How to configure your application
* [JSON REST services](./rest-json): How to write JSON REST services
* [Hibernate ORM and RESTEasy](./hibernate-orm-resteasy): Exposing a CRUD service over REST using Hibernate ORM to connect to a PostgreSQL database
* [Hibernate ORM with Panache and RESTEasy](./hibernate-orm-panache-resteasy): Exposing a CRUD service over REST using Panache to connect to a PostgreSQL database
* [Scheduling periodic tasks](./scheduling-periodic-tasks): How to schedule periodic jobs
* [Using Web Sockets](./using-websockets): Demonstrate how to use web sockets and serve static assets
* [Startup and Shutdown actions](./application-lifecycle-events): Explains how to execute code when the application starts and stops
* [Validation with Hibernate Validator](./validation): How to use Hibernate Validator/Bean Validation in your REST services 
* [REST Client](./rest-client): How to use MicroProfile's REST Client
* [OpenTracing and Jaeger](./using-opentracing): How to use MicroProfile OpenTracing and Jaeger to monitor application performances
* [Spring DI compatibility layer](./using-spring-di): How to use our Spring Dependency Injection compatibility layer
* [Infinispan Client](./infinispan-client): How to use Infinispan Client. Covers creating caches and simple get/put.

There is documentation published at <https://quarkus.io> (docs' [sources are here](https://github.com/quarkusio/quarkus/tree/master/docs/src/main/asciidoc)).

## Prerequisites

* [Maven 3.5.3+](https://maven.apache.org/install.html)
* [Java - OpenJDK 1.8+](https://adoptopenjdk.net/)
* [GraalVM rc12+](https://www.graalvm.org/)
