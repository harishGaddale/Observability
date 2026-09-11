podman pull quay.io/prometheus/prometheus:v3.14.0

podman run -d --name prometheus314 -p 9090:9090 quay.io/prometheus/prometheus:v3.14.0
