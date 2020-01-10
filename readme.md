# My Swift for TensorFlow Dockerfile

## Build

```bash
$ sudo docker build -t s4tf ./docker
```

## Run

```bash
$ sudo docker run -it --rm --gpus all -v $(pwd):/workspace s4tf bash
```
