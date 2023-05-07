# observability_stack
My current observability stack

Components:
  - [Grafana](https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/)
  - [Prometheus](https://prometheus.io/docs/prometheus/latest/installation/#using-docker)
  - [statsD exporter](https://github.com/prometheus/statsd_exporter) (for Mastodon)
  - [Postgres exporter](https://github.com/prometheus-community/postgres_exporter) (for Mastodon)
  - [NGINX exporter](https://github.com/nginxinc/nginx-prometheus-exporter) (connected to host NGINX)
  - [Node Exporter](https://github.com/prometheus/node_exporter) (running on host)

Dashboards I'm using:
  - [Postgres exporter](https://grafana.com/grafana/dashboards/9628-postgresql-database/)
  - [Mastodon](https://grafana.com/grafana/dashboards/17492-mastodon-stats/)
  - [NGINX exporter](https://github.com/nginxinc/nginx-prometheus-exporter/blob/main/grafana/README.md)
  - [Node exporter](https://grafana.com/grafana/dashboards/1860-node-exporter-full/)
  - Prometheus - "default" grafana one
  - Grafana - "default" grafana one

statsd mapping file and ideas from [here](https://ipng.ch/s/articles/2022/11/27/mastodon-3.html) (Great article, thanks!)

Try it [here](https://grafana.shantih19.xyz).
