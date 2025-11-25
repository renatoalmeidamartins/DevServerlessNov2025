# DevServerlessNov2025

## Material e acesso a laboratórios
- [Online Course supplement](https://skillbuilder.aws/learn/7UUHTNPDKS/developing-serverless-solutions-on-aws--course-supplement-ocs/PSKFU4NPQQ)
- [Acesso ao material e laboratórios](https://us-east-1.student.classrooms.aws.training/class/ilt%236ZPULEf9Us5R86iYkX5UYr), Ao abrir este link, você verá uma tela para fazer login, parecida com a tela abaixo<br><img src="./lab-login.jpg" alt="login options" width="300" height="300"/><br>Você deve fazer login com o mesmo email usado para registrar-se no curso.<br>
A forma tipicamente recomendada para login é usando o "builder id". O problema é que normalmente este funciona apenas com emails pessoais. Se você se registrou com a sua conta corporativa, escolha "One-time email passcode". Caso este não funcione (por exemplo, por bloqueio no seu servidor de email), utilize "Organization SSO". A opção de SSO talvez te impeça de realizar os labs corretamente.<br>Uma vez que você esteja registrado, pode ser que receba um "acesso negado". Me avise, que acrescento o email que você está utilizando à classe.
- [Webinars de preparação para certificação](https://aws.amazon.com/partners/training/certification/?)


## Links do dia 1
- [AWS Builder center, um ponto de partida para diversos recursos de apoio a desenvolvedores](https://builder.aws.com/)
- [Bedrock Agentcore](https://aws.amazon.com/blogs/aws/introducing-amazon-bedrock-agentcore-securely-deploy-and-operate-ai-agents-at-any-scale/)
- [Lente de serverless, na well-architected framework](https://docs.aws.amazon.com/wellarchitected/latest/serverless-applications-lens/welcome.html?did=wp_card&trk=wp_card)
- Alguns serviços, tradicionalmente consumidos como não-serverless, que oferecem tem um tempo, "versões" serverless
  - [Elasticache](https://aws.amazon.com/blogs/aws/amazon-elasticache-serverless-for-redis-and-memcached-now-generally-available/)
  - [OpenSearch](https://docs.aws.amazon.com/opensearch-service/latest/developerguide/serverless.html)
  - [Aurora](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless-v2.html)
  - [Reshift](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-serverless.html)
  - [EMR](https://docs.aws.amazon.com/emr/latest/EMR-Serverless-UserGuide/emr-serverless.html)
- [12 factor app, boas ideias para aplicações serverless](https://12factor.net/)
- [Video do Rick Houlihan descrevendo padrões avançados de projeto no DynamoDB](https://www.youtube.com/watch?v=xfxBhvGpoa0)
- [Melhores práticas para uso de DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/best-practices.html)
- [Autenticacão de pedidos usando SigV4](https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html)
- [Micro-serviços de uma só função podem ser expostos por uma URL de função Lambda](https://aws.amazon.com/blogs/aws/announcing-aws-lambda-function-urls-built-in-https-endpoints-for-single-function-microservices/)
- [Comparação entre APIs REST e HTTP](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-vs-rest.html)
- [Desenho de uma API GraphQL usando AppSync](https://docs.aws.amazon.com/appsync/latest/devguide/blank-import-api.html)
- [Arquitetura de APIs de GraphQL](https://aws.amazon.com/blogs/architecture/how-to-architect-apis-for-scale-and-security/)
- [Planos diversos no Cognito com funcionalidades diferentes](https://aws.amazon.com/blogs/aws/improve-your-app-authentication-workflow-with-new-amazon-cognito-features/)
- [Exemplo "hello world"  no CDK](https://docs.aws.amazon.com/cdk/v2/guide/hello-world.html)
- [Repo do SAM - Serverless Application model](https://github.com/aws/serverless-application-model)
- [Repo com os templates de app do SAM](https://github.com/aws/aws-sam-cli-app-templates)
- [Framework de Amplify](https://docs.amplify.aws/react/)
- [Retries em invocação assíncrona de Lambda](https://docs.aws.amazon.com/lambda/latest/dg/invocation-async-error-handling.html)
- [Fontes parceiras para eventos no EventBridge](https://aws.amazon.com/blogs/aws/amazon-eventbridge-event-driven-aws-integration-for-your-saas-applications/)
- [Lista completa de parceiros suportados para EventBridge](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-saas.html#eb-supported-integrations)
- [Geração de code binding com base nos eventos do Schema Registry](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-schema-code-bindings.html)

## Dia 2
- [Fases de retry do SNS](https://docs.aws.amazon.com/sns/latest/dg/sns-message-delivery-retries.html)
- [Como Lambda processa registros de fontes de eventos de stream e filas](https://docs.aws.amazon.com/lambda/latest/dg/invocation-eventsourcemapping.html)
- [Melhores práticas para funções Lambda](https://docs.aws.amazon.com/lambda/latest/dg/best-practices.html)
- [Configuração de concorrência em Lambda](https://docs.aws.amazon.com/lambda/latest/dg/configuration-concurrency.html)
- [Usando RDS Proxy](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/rds-proxy.howitworks.html)
- [Conexão a recursos usando Step Functions](https://docs.aws.amazon.com/step-functions/latest/dg/connect-to-resource.html)
- [Linguagem de estados (state language) usada pelo Step Functions](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-amazon-states-language.html)
