# Google Cloud Platform Cloud Shell

## Pontos importantes:
- Documentação oficial do Cloud Shell: [Cloud Shell](https://cloud.google.com/shell?hl=pt-br)
- Guias de início rápido: [Implantar um app do App Engine usando o Cloud Shell] (https://cloud.google.com/shell/docs/deploy-app-engine-app?hl=pt-br)
- [Criar e implantar um app da Web conteinerizado] (https://cloud.google.com/shell/docs/deploy-gke-app?hl=pt-br)
- [Implantar um app do Cloud Run usando o Cloud Shell] (https://cloud.google.com/shell/docs/deploy-cloud-run-app?hl=pt-br)

### Exemplo de aplicação
- Google App Engine - Quarkus Hello World 
  Link: [Quarkus Application on Google App Engine Standard with Java 11](https://github.com/GoogleCloudPlatform/java-docs-samples/tree/main/appengine-java11/quarkus-helloworld)

- Para executar no Cloud Shell:
  - mvn clean install
  - cd target
  - java -jar *NOME DO ARTEFATO GERADO*