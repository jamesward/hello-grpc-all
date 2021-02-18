hello grpc-all
-----------------------------

Run Locally:
```
./gradlew run
```

Containerize:
1. [Install pack](https://buildpacks.io/docs/tools/pack/)
2. Build the container:
```
pack build hello-grpc-all --builder gcr.io/buildpacks/builder
```
3. Run it:
```
docker run -it hello-grpc-all
```
