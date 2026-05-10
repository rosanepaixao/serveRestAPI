#  Bootcamp #01 Curso Udemy- Dominando Postman Do Teste Manual a Performance APIs
Teste de API Rest do manual a CI/CD

## o que é 
Este repositório foi criado para o bootcamp de Teste de API Rest

## Tecnologia utilizadas
- Postman versão web
- node version v20.11.0
- newman version 6.2.1
- newman-report-html

## Documentações
- Análise Técnica: Analise/
- Doc API: [Consulte Swagger](https://serverest.dev/?lang=pt-BR)

## Como instalar o ambinente 
- Primeiro: Instale o node em seu computador [Baixe aqui] (https://nodejs.org/en/download)
- Segundo: Realize a instalação do newman de forma global [Baixe aqui a dependencia] (https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: Realize a instalação a dependencia dos relatórios (Opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```

## Como rodar os testes

### Pelo Postman web ou desktop
- Importr a collection e o environment
- Execute o teste de forma manual ou automatizada

### Pelo newman

- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
  ```
  newman run ServerRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
  ```
  - Execute os teste com relatório
  ```
  newman run ServerRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
  ```

## Entre em contato

  email: qarosane@gmail.com
  
  redes socias: https://www.linkedin.com/in/qarosanepaixao/
