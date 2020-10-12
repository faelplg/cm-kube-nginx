Curso de Microsserviços:
# Desenvolvimento de Aplicações Modernas e Escaláveis com Microsserviços

## Módulo: DEVOPS

### Exercício: Utilizando K8s
* Autor: Rafael Goulart
  * E-mail cadastrado: rafaelgoulart@residuall.org
  * E-mail pessoal: faelplg@gmail.com

#### Tarefa 1: Servidor Web - Nginx
* Nome do artefato: `cm-kube-nginx`
* [Repositório do GitHub (este)](https://github.com/faelplg/cm-kube-nginx)

Resolução:
* Criação do `deployment.yaml`;
  * Configuração simples especificando um container com `nginx:1.18-alpine`;
* Criação do `configmap.yaml`;
  * Neste arquivo quero definir o conteúdo do arquivo html que irá exibir a mensagem "Code.Education Rocks!".
* Criação de um volume no `deployment.yaml` que utiliza o ConfigMap criado;
* Montagem desse volume na pasta `/usr/share/nginx/html`, copiando a alteração realizada;
* Criação de um serviço para expor o NGINX;

#### Tarefa 2: Configuração do MySQL
* Nome do artefato: `cm-kube-mysql`
* [Repositório do GitHub](https://github.com/faelplg/cm-kube-mysql)

Resolução:
* A
* B

#### Tarefa 3: Desafio Go!
* Nome do artefato: `cm-kube-go`
* [Repositório do GitHub](https://github.com/faelplg/cm-kube-go)

Resolução:
* A
* B
