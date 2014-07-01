custom-conf-multi
=================

no transitive dependency resolution for custom configs

##Run

```
./gradlew client:dependencies 
```

```
:client:dependencies

------------------------------------------------------------
Project :client
------------------------------------------------------------

archives - Configuration for archive artifacts.
No dependencies

default - Configuration for default artifacts.
No dependencies

myconf
\--- project :common

BUILD SUCCESSFUL

Total time: 0.79 secs
```