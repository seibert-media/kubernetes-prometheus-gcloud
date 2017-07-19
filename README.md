# Prometheus Configs

## Test prometheus config:

```
go get -u github.com/prometheus/prometheus/cmd/prometheus
prometheus -config.file prometheus.yaml
```

## Test alertmanager config:
	
```
go get -u github.com/prometheus/alertmanager/cmd/alertmanager
alertmanager -config.file alertmanager.yaml
```
