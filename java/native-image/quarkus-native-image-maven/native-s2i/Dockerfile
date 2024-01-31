FROM quay.io/quarkus/ubi-quarkus-graalvmce-s2i:jdk-17.0.8

LABEL io.k8s.description="Quarkus.io S2I image for building Kubernetes Native Java GraalVM applications and running its Native Executables" \
io.k8s.display-name="Quarkus.io S2I (GraalVM Native)" \
io.openshift.expose-services="8080:http" \
io.openshift.s2i.destination="/tmp" \
io.openshift.s2i.scripts-url="image:///usr/libexec/s2i" \
io.openshift.tags="builder,java,quarkus,native" \
maintainer="Quarkus Team <quarkus-dev@googlegroups.com>"
