# pinot-docker-bootstrap

This project uses docker compose to bootstrap an apache pinot cluster. It builds upon the 
climate change analysis demo by @kbastani [climate change analysis](https://github.com/kbastani/climate-change-analysis)
to strip out Apache superset and bootstrap a basic demo cluster.

## Usage

Intended usage of the bootstrap is to help developers start a base cluster for building applications with Apache Pinot
in development only. **Not for production use.**

```bash
$ docker-compose up -d
$ docker-compose logs -f --tail=100
```

At this point you will be ready to access your cluster at [localhost:9000](http://localhost:9000)
