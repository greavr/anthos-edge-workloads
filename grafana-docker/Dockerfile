from grafana/grafana

COPY gcp.yaml /etc/grafana/provisioning/datasources/gcp.yaml
COPY dashboards.yaml /etc/grafana/provisioning/dashboards/dashboards.yaml
COPY default.json /etc/grafana/provisioning/dashboards/default.json
COPY grafana.ini /etc/grafana/grafana.ini

EXPOSE 3000