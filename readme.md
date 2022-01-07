***This project has a docker-compose that shows the integrations between
Micrometer, Prometheus and Grafana.***

- Micrometer is responsable for export data to Prometheus.
- Prometheus, is used to collect metrics from Micrometer and could be used to design graphics, but...
- Grafana, is used to connect with basically everyone datasource and
generates graphs in a simple way, for example, importing graphs pre-defined

Basically, the workflows is:

![Micrometer in your appp](images/micrometer.png) 
![](images/arrow.webp)
![Prometheus](images/prometheus.png)
![](images/arrow.webp)
![Grafana](images/grafana.jpg)
![](images/arrow-back.png)
![User](images/user.png)
