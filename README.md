# Prometheus on docker for ARM 32-bit v6 CPU
Based on the official prometheus Dockerfile, replacing the base image and binary with ARMv6 builds.

Download the prometheus binary for arm32v6 from https://github.com/prometheus/prometheus/releases and extract it to the directory with the Dockerfile.

To build the image run: 
```
docker build -t whatever:latest .
```
