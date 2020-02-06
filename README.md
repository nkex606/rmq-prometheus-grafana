# rmq-prometheus-grafana

RabbitMQ + Prometheus + Grafana example

**Note**

RabbitMQ container 需進去 enable prometheus plugin

``` bash
rabbitmq-plugins enable rabbit_prometheus
```

不然就要選擇其他rabbitmq image, 例如官方範例：

    image: pivotalrabbitmq/rabbitmq-prometheus:3.9.0-alpha.183-2020.01.07
