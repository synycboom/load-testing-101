# Load testing 101
slide: https://slides.com/synycboom/load-testing-101/

## How to run
Run grafana and influxdb
```
docker-compose up grafana influxdb
```

Run the test
```
docker-compose run k6 run /scripts/smoke.js
```