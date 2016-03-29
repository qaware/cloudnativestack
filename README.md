# Cloud Native Stack Technology Radar

Open Source Components for building a Cloud Native Stack.
You may also want to check out our [Big Data Landscape](https://github.com/qaware/big-data-landscape) and our [lecture on Cloud Computing (german)](https://github.com/adersberger/cloudcomputing).

![Cloud Native Stack Big Picture](cloud-native-stack.png "Cloud Native Stack Big Picture")

## Cluster Scheduler
 * [Apache Mesos](http://mesos.apache.org)
 * [Docker Swarm](https://www.docker.com/products/docker-swarm)
 * [Hadoop YARN](http://hortonworks.com/hadoop/yarn)
 * [CoreOS fleet](https://github.com/coreos/fleet)
 * [Nomad](https://www.nomadproject.io)

## Cluster Orchestrator
 * [Kubernetes](http://kubernetes.io)
 * [Docker Compose](https://docs.docker.com/compose)
 * [Kontena](http://www.kontena.io)
 * [VAMP](http://vamp.io)
 * [Marathon](https://mesosphere.github.io/marathon) + [Chronos](http://mesos.github.io/chronos)
 * [Nulecule](http://www.projectatomic.io/docs/nulecule)
 * [Panamax](http://panamax.io)
 * [Apache Aurora](http://aurora.apache.org)
 * [Decking](http://decking.io)
 * [Rancher](https://github.com/rancher/rancher)
 * [Cloudify](http://getcloudify.org)
 * [Singularity](https://github.com/HubSpot/Singularity)
 * [Apache Brooklyn](https://brooklyn.apache.org)
 * [Lattice](http://lattice.cf)
 * [Helios](https://github.com/spotify/helios)

## Microservice Framework
 * [Spring Cloud](http://projects.spring.io/spring-cloud) Spring Boot + several cloud modules & microservices
 * [Lagom](https://www.lightbend.com/lagom) Microservice Framework from Lightbend based on Akka et al.
 * [Seneca](http://senecajs.org)
 * [hapi.js](http://hapijs.com)
 * [hook.io](https://hook.io)
 * [Microserver](https://github.com/aol/micro-server)

## Distributed Systems Services

### Configuration & Coordination
 * [ZooKeeper](https://zookeeper.apache.org), Paxos-based
 * [etcd](https://coreos.com/etcd/docs/latest), Raft-based
 * [Consul](https://www.consul.io), Raft-based
 * [doozerd](https://github.com/ha/doozerd), Paxos-based
 * [atomix](https://github.com/atomix/atomix), Raft-based
 * [Serf](https://www.serfdom.io), Gossip-based
 * [Netflix Archaius](https://github.com/Netflix/archaius), battle-proven @ Netflix, well-integrated, Java-based
 * [confd](http://www.confd.io)
 * [Spring Cloud Config](http://cloud.spring.io/spring-cloud-config)
 
### Service Discovery
 * [Netflix Eureka](https://github.com/Netflix/eureka), battle-proven @ Netflix, well-integrated, Java-based
 * [Consul](https://www.consul.io)
 * [SkyDNS](https://github.com/skynetservices/skydns)
 * [Hyperbahn](https://github.com/uber/hyperbahn)
 * [Skydock](https://github.com/crosbymichael/skydock)
 * [SmartStack](http://nerds.airbnb.com/smartstack-service-discovery-cloud)
 * [bamboo](https://github.com/QubitProducts/bamboo)
 * [WeaveDNS](http://docs.weave.works/weave/latest_release/weavedns.html)
 * [Marathon-LB](https://github.com/mesosphere/marathon-lb)

### Edge Server
 * [Netflix Zuul](https://github.com/Netflix/zuul), battle-proven @ Netflix, well-integrated, Java-based ([Intro](http://techblog.netflix.com/2013/06/announcing-zuul-edge-service-in-cloud.html))
 * [Traefik](http://traefik.github.io)
 * [VULCAN](http://vulcand.github.io)
 * [KONG](https://getkong.org)
 * [tyk](https://tyk.io)
 * [Weave Flux](https://github.com/weaveworks/flux)

### Monitoring & Logging
 * [Netflix Turbine](https://github.com/Netflix/Turbine), battle-proven @ Netflix, well-integrated, Java-based
 * [Netflix Atlas](https://github.com/Netflix/atlas), battle-proven @ Netflix, well-integrated, Java-based
 * [Spring Cloud Sleuth](http://cloud.spring.io/spring-cloud-sleuth)
 * [Zikin](https://github.com/openzipkin/zipkin)
 * [Prometheus](https://prometheus.io)
 * [Kibana](https://www.elastic.co/products/kibana)
 * [Grafana](http://grafana.org)
 * [Sensu](https://sensuapp.org)
