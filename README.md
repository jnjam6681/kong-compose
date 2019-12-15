## Kong API Gateway

#### Set Environment Variables
You can use `.env` file or default values from docker-compose
if you want to change it. Just rename `env-example` file
```
mv env-example .env
```

#### Prometheus
If you want to reload configure with command.
Uncommand to use feature.
```
- '--web.enable-lifecycle'
```
Reload configure
```
localhost:9090/-/relaod
```
