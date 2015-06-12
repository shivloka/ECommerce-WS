# ECommerce-WS
ECommerce-WS - OrderService using JAX-WS libraries.

1. This Project needs ECommerce-shared to be compiled to a jar and installed in the maven repo locally.
2. It uses the project during the maven build.
3. To install jar into the maven repo use: 
    mvn install:install-file -Dfile=<path-to-file> -DgroupId=<group-id> -DartifactId=<artifact-id> -Dversion=<version> -Dpackaging=<packaging>
