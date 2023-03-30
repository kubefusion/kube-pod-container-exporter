# kube-pod-container-exporter

kube-pod-container-exporter is a simple exporter for Kubernetes pods' containers. It exposes Kubernetes pods' containers cpu and mem metrics.

## Usage

All command line flags:

[embedmd]:# (_output/help.txt)
```txt
$ kube-pod-exporter -h
Usage of _output/linux/amd64/kube-pod-exporter:
  -container-runtime-endpoint string
    	The endpoint to connect to the CRI via. (default "passthrough:///unix///var/run/dockershim.sock")
  -listen-address string
    	The address the kube-pod-exporter HTTP server should listen on.
```