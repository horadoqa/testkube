# TESTKUBE

## Dashboard

[Acessando o Testkube local via Browser](http://localhost:8080/)

<div align="center">

![Dashboard](./images/testkube/dashboard-local.png)

</div>

O administrador nesta demonstração tem o seguinte e-mail e senha: 

> admin@example.com/password

## Login

<div align="center">

![login localhost](./images/testkube/login-localhost.png)

</div>

## Criando conta

<div align="center">

![Criando Conta](./images/testkube/criando-conta-testkube.png)

</div>

## Configurando o primeiro Workflow


<div align="center">

![Create your first test workflow](./images/testkube/creat-workflow.png)

</div>

## Criando o Workflow de Teste

<div align="center">

![Create Workflow](./images/testkube/create-from-wizard.png)

</div>

## Criando o teste

<div align="center">

![Create Test](./images/testkube/create-test.png)

</div>

## Configurando a ferramenta que será utilizada no teste

- Name: test.k6.io
- Labels: testkube.io/name:k6
- Template: k6
- K6 Version

Conforme a imagem abaixo:

<div align="center">

![Create Test](./images/testkube/create-test-2.png)

</div>

## Criando a configuração que será utilizada no test

- [Git](../docs/git.md), utilizando um repositório com o script de teste.
- [File](../docs/file.md), indicando o arquivo com o script de teste.
- [String](../docs/string.md), com o script de teste.

Próximos passos... [Verificando consumo CPU/Memória dos Nodes e Pods](../prometheus-grafana-k8s/instalação.md)
