# Redis => Logstash => Elasticsearch 

## Usage:
```
docker run -d -p 6379:6379 -p 9200:9200 petitchevalroux/rel
```
Elasticsearch data are located in /data, to mount as a volume use :
```
-v /path/to/host/data/:/data
```

Available on:
* [docker hub](https://registry.hub.docker.com/u/petitchevalroux/rel/)
* [github](https://github.com/petitchevalroux/docker-rel)

## About me
http://petitchevalroux.net