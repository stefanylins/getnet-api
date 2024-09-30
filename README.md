
# Automação API - Getnet

Esse projeto foi realizado como parte do processo seletivo para a empresa CWI Software.

Desenvolva o script da automação seguindo as informações a seguir:

Documentação = (https://reqres.in/)
URI = (https://reqres.in/api/)

> Passos:

1 - Validar o script de "CREATE" método "POST” cobertura de testes em Rest-
Assured da API

2 - Validar cobertura de Status Code, Campos obrigatórios e Contrato

3 – Desenvolver com POJOs.


> IMPORTANTE!

O script da automação foi implementada com Postman com Javascript + Newman, dado o curto prazo e a maior familiaridade com essa tecnologia em relação à stack principal desejada.



## Tecnologias utilizadas

- Postman
- Newman
- Javascript


## Instalação

Instalar o `node.js` pelo site
(https://nodejs.org/pt)

Instalar o `newman` global
```bash
  cd /c/
npm install -g newman
```     
Criar e acessar a pasta `getnet-api`
```bash
mkdir getnet-api
cd /c/getnet-api
```


## Rodando os testes

Para rodar os testes pela CLI, execute o seguinte comando

```bash
  newman run ReqresAPI.postman_collection.json -e ReqresAPI.postman_environment.json -r cli
```
Instalar as dependências para gerar o relatório dos testes pelo Postman
```bash
 npm install -g newman-reporter-html
```
Gerar o relatório pelo Newman
```bash
newman run ReqresAPI.postman_collection.json -e ReqresAPI.postman_environment.json -r cli, htmlextra
```


## Relatórios de testes

Após executar os testes, os relatórios gerados estarão salvos na pasta `getnet-api/newman` , possibilitando abrir e visualizar pelo navegador os resultados.


## Considerações Finais

O principal desafio foi equilibrar a necessidade de entregar uma solução funcional dentro do prazo com a stack ideal desejada. Decidi optar pelo Postman com Javascript + Newman por ser mais familiar e garantir uma automação eficiente no tempo disponível. Essa escolha me possibilitou uma entrega de qualidade, com testes confiáveis e uma organização clara do código. Estou muito feliz por conseguir concluir com sucesso o desafio :D




