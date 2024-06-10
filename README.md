# Aubay - Mensageria e Pulsar
* primeiro vamos botar o pulsar no ar com docker

```shell
docker run -it -p 6650:6650  -p 8080:8080 --mount source=pulsardata,target=/pulsar/data --mount source=pulsarconf,target=/pulsar/conf apachepulsar/pulsar:3.1.3 bin/pulsar standalone
```
# Rodar a aplicação
 Rode a classe principal :)
