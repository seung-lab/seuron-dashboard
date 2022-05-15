FROM grafana/grafana:latest
COPY grafana /etc/grafana
COPY dashboards /etc/dashboards
USER root
RUN chown -R grafana /etc/grafana && chown -R grafana /etc/dashboards
USER grafana
