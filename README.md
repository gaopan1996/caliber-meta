# caliber-meta
Meta repository for Caliber v2 microservice ecosystem. Contains wiki for both the v2 MSA and Angular UI. 

To get started with Caliber, install meta and use the `meta git clone https://github.com/revaturelabs/caliber-meta.git` command.

## Infrastructure services
Caliber leverages the microservice architectural design pattern. There are currently three infrastructure services: Zuul, Eureka, and Spring Cloud Config.

### Spring Cloud Config
Necessary environment variables: 
```
CALIBER_CONFIG_GIT_URI : https://gitlab.com/revalution/caliber-configuration.git
CALIBER_CONFIG_GIT_USERNAME : your Gitlab user
CALIBER_CONFIG_GIT_PASSWORD : your Gitlab password
CALIBER_CONFIG_SERVER_URL : http://localhost:8888/
```

### Netflix Eureka
Necessary environment variables:
```
CALIBER_EUREKA_SERVER_URL : http://localhost:8761/
```
For more information on the Meta tool: visit https://github.com/mateodelnorte/meta 
