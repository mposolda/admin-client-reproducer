# admin-client-reproducer

Run this project with:

```
mvn clean install -s .github/maven-settings.xml -U
```

And you will see the error:
```
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  11.067 s
[INFO] Finished at: 2024-11-15T15:24:08+01:00
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal on project keycloak-admin-client-reproducer: Could not resolve dependencies for project org.keycloak:keycloak-admin-client-reproducer:jar:999.0.0-SNAPSHOT: The following artifacts could not be resolved: io.grpc:grpc-netty:jar:1.65.0.redhat-00001, io.grpc:grpc-protobuf:jar:1.65.0.redhat-00001, io.vertx:vertx-core:jar:4.5.9.redhat-00001, io.grpc:grpc-stub:jar:1.65.0.redhat-00001, io.grpc:grpc-api:jar:1.65.0.redhat-00001: Could not find artifact io.grpc:grpc-netty:jar:1.65.0.redhat-00001 in redhat-ga-repository-group (https://maven.repository.redhat.com/ga/) -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/DependencyResolutionException

```
