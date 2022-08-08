# Solarshed Containerized (runs on RPi)

```
docker run --name solarshed -d -p 5000:5000 \
--device /dev/ttyUSB0:/dev/ttyUSB0 --restart=always \
--priviledged ghcr.io/truncj/solarshed
```

![setup](./images/solar.jpg)