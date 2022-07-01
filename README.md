# _Prometheus JSON sandbox_

#### _Small repo for testing out prometheus exporters and configs_

#### By _**wanieldilson**_

## Technologies Used

* _Prometheus_
* _Grafana_
* _nginx_
* _Docker_

## Description

_Running `docker compose up` will spin up nginx, prometheus, Grafana and a JSON exporter for prometheus.  You can use this combination of stuff to test how prometheus may behave when pointed at your new API_

## Setup/Installation Requirements

* _Docker_

_You should only need a working Docker installation for this to work.  It has only been tested on Ubuntu_

## Usage

_Clone this repo, run `docker-compose up` and then point your browser to http://localhost:9090/_
_On the Graph tab search `subnet_statistics_remaining_ips` and you'll see the example metrics in the UI_
![image](https://user-images.githubusercontent.com/68431297/176916978-5b7b32e9-763d-486c-a3e1-0fa1d74e6e92.png)

