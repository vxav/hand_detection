## Raise hand test app

- Plug a camera to the machine.

```
docker run --rm -it --device=/dev/video0:/dev/video0 vxav/raise-hand:latest
```

Based off of https://github.com/paytonshaltis/arm-raise-detection
