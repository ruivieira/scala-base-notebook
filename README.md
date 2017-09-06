# scala-base-notebook
An image for running Scala Jupyter notebooks and Apache Spark in the cloud on OpenShift

## Running

### Docker

To run just the Docker container, first build it with

```
make build
```

and run it with

```
make run
```

The default Jupyter password is `developer`.

### OpenShit

Create a new app using

```
oc new app https://github.com/ruivieira/scala-base-notebook
```