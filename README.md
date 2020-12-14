# antora-docs

## How to run
To generate a docs site, please run the following command:
```
docker run -u $(id -u) -v $PWD:/antora:Z -t antora/antora --stacktrace antora-playbook.yml 
```