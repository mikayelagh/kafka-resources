# Apache/Confluent Kafka Resources

## Kafka Docs
https://kafka.apache.org/documentation/


https://docs.confluent.io/platform/current/tutorials/cp-demo/docs/on-prem.html

https://docs.confluent.io/platform/current/control-center/brokers.html#c3-brokers-consumption-metrics C3

https://docs.confluent.io/platform/current/multi-dc-deployments/replicator/replicator-docker-tutorial.html#replicator Replicator Demo

SBC - https://docs.confluent.io/platform/current/kafka/sbc/index.html#sbc

SBC - https://docs.confluent.io/platform/current/kafka/sbc/configuration_options.html#sbc-config-enable

MDS https://docs.confluent.io/platform/current/kafka/configure-mds/index.html

https://www.confluent.io/white-paper/optimizing-your-apache-kafka-deployment/. Optimization


## Kafka Internals/Theory

https://strimzi.io/blog/2021/12/17/kafka-segment-retention/. Deep dive into Apache Kafka storage internals: segments, rolling and retention

https://developers.redhat.com/articles/2022/05/03/fine-tune-kafka-performance-kafka-optimization-theorem


## KSQL
https://docs.confluent.io/platform/current/ksqldb/integrate-ksql-with-confluent-control-center.html#configuration-settings-for-ksqldb-and-c3-short



## Security
https://docs.confluent.io/platform/current/tutorials/cp-demo/docs/on-prem.html#security

https://docs.confluent.io/platform/current/control-center/security/c3-rbac.html#controlcenter-security-rbac C3 RBAC

https://docs.confluent.io/platform/current/security/general-overview.html#security  Security

https://github.com/confluentinc/confluent-platform-security-tools


## Schema
https://docs.confluent.io/platform/current/schema-registry/schema-validation.html#schema-validation


## Compatibility Matrix
https://cwiki.apache.org/confluence/display/KAFKA/Compatibility+Matrix

## ksqlDB and Kafka Streams

https://docs.confluent.io/platform/current/streams-ksql.html

https://kafka.apache.org/documentation/streams/

## Kafka Clients
https://docs.confluent.io/platform/current/clients/index.html 

https://www.confluent.io/blog/kafka-client-cannot-connect-to-broker-on-aws-on-docker-etc/


## Monitoring
https://github.com/confluentinc/jmx-monitoring-stacks

https://www.confluent.io/blog/confluent-datadog-integration-kafka-monitoring-metrics/

https://docs.confluent.io/platform/current/control-center/installation/clients.html. - Interceptors


## Kafka Utilities

Kafkacat: https://docs.confluent.io/platform/current/app-development/kafkacat-usage.html

kcat is the project formerly known as as kafkacat https://github.com/edenhill/kcat

Kafdrop – Kafka Web UI https://github.com/obsidiandynamics/kafdrop

Kafka GUI - https://github.com/tchiotludo/akhq

Kafka Ui - https://github.com/provectus/kafka-ui.   ,  https://akhq.io/

Redpanda Kafka Console - https://github.com/redpanda-data/console

Kryptonite - An SMT for Kafka Connect https://github.com/hpgrahsl/kafka-connect-transform-kryptonite

Fluent Kafka Streams Tests https://github.com/bakdata/fluent-kafka-streams-tests

Xinfra Monitor monitors the availability of Kafka clusters by producing synthetic workloads using end-to-end pipelines to obtain derived vital statistics - E2E latency, service produce/consume availability, offsets commit availability & latency, message loss rate and more.
https://github.com/linkedin/kafka-monitor

Burrow: Kafka Consumer Monitoring (LinkedIn) https://engineering.linkedin.com/apache-kafka/burrow-kafka-consumer-monitoring-reinvented

Parallel Apache Kafka client wrapper with client side queueing, a simpler consumer/producer API with key concurrency and extendable non-blocking IO processing.
https://github.com/confluentinc/parallel-consumer

CLI for Kafka Connect https://github.com/kcctl/kcctl

(!) https://github.com/linkedin/cruise-control

(!) https://github.com/yahoo/CMAK

(!) https://github.com/echojc/kafka-offset-exporter

Karapace - Your Kafka essentials in one tool https://github.com/aiven/karapace. https://karapace.io/

https://softwaremill.com/kafka-visualisation/ - Kafka Visualization

https://github.com/kcctl/kcctl
Kafka connect utility

https://kafka.esque.at/

## DevOps

https://github.com/HermesGermany/galapagos

https://github.com/kafka-ops/julie

https://julieops.readthedocs.io/en/latest/index.html

https://videos.confluent.io/watch/dGXUXUvF5xtRDix7xTPPzt

https://www.openservicebrokerapi.org/

https://github.com/strimzi  Apache Kafka on k8s, A Kubernetes and OpenShift operator for Apache Kafka

https://slack.engineering/building-self-driving-kafka-clusters-using-open-source-components/

https://github.com/StephenSorriaux/ansible-kafka-admin


## HA, DR, Deployment Architecture, K8S

https://www.confluent.io/blog/how-to-survive-a-kafka-outage/

https://www.wise.jobs/2021/09/23/running-kafka-in-kubernetes-part-1-why-we-migrated-our-kafka-clusters-to-kubernetes/

https://www.confluent.io/kafka-summit-london18/kafka-in-containers-in-docker-in-kubernetes-in-the-cloud/

https://www.confluent.io/kafka-summit-lon19/running-kafka-in-kubernetes-practical-guide/

https://learnk8s.io/kafka-ha-kubernetes

https://github.com/grepplabs/kafka-proxy 

## Examples and POCs

https://github.com/streamthoughts/kafka-streams-examples/blob/master/src/main/java/io/streamthoughts/kafka/streams/examples/wordcount/topology/WordCountProcessorTopology.java
https://github.com/streamthoughts/kafka-streams-examples/blob/master/src/main/java/io/streamthoughts/kafka/streams/examples/TopologyDriverConfig.java
https://github.com/streamthoughts/kafka-streams-examples/blob/master/src/main/java/io/streamthoughts/kafka/streams/examples/utils/Utils.java

https://issues.apache.org/jira/browse/KAFKA-8296


ksqlDB GraphQL poc https://github.com/gklijs/ksqlDB-GraphQL-poc/tree/just-persons

