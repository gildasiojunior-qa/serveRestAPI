# BootCamp Qualiters Club
Teste de API Rest do manual a CI/CD

Criação de teste de API utilizando postman, newman e newman-htmlextra

## O que é
Este repositório foi criado para o bootcamp de Testes de API Rest.

## Tecnologias utilizadas
- Postman versão web
- node version v18.18.2
- Newman v6.2.2
- Newman-reporter-html

## Documentações
 - Doc da API: [Consulte Swagger](https://serverest.dev/)

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global[baixe aqui a dependência](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: realize a instalação da dependência dos relatórios (opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```

## Como rodar os testes


### Pelo Postman web ou dektop
- Import a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo newman
- Abra seu console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute os testes com relatório
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```

### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato

email: junior_pimentel@live.com

redes sociais: https://www.linkedin.com/in/gildasio-junior-71b15814a/
