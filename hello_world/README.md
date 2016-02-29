# Storm first demo: hello_world

## Environment setup

###after build gradle multiple projects. generate eclipse project and build fatJar

```bash
cd hello_world

gradle cleanEclipse eclipse clean fatJar
```

###upload jar to storm server

```bash
storm jar /home/strom01/Desktop/hello_world-all.jar com.wdxxl.storm.cookbook.HelloWorldTopology stormHelloWorld
```

###Web Access

http://localhost:8080/index.html