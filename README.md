# Elastic Stack & Observability

The Elastic Stack (also known as ELK Stack) is comprised of the following products: Elasticsearch, Kibana, Beats, and Logstash. Obtain data reliably and securely from any source, in any format; then perform searches, analyzes and visualizations.

[Official](https://www.elastic.co)

## Setup

```
docker network create -d bridge observability
docker compose up -d
```
`Dashboard` -> http://localhost:5601

<img width="1717" alt="image" src="https://github.com/vmoney-bsb/vmoney-api/assets/63156114/1f71d242-602a-45e8-8a58-5823ac5c1f44">

<img width="1228" alt="image" src="https://github.com/ivsonv/elastic-search-observability/assets/63156114/701f4bac-2784-4e80-9fb9-64ba3efa71e8">
<br>

`heartbeat` -> kibana -> observability -> uptime
<img width="1715" alt="image" src="https://github.com/ivsonv/elastic-search-observability/assets/63156114/c214c8c9-d091-467e-be4c-426316a7ca5f">
