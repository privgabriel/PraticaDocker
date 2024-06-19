# PraticaDocker

## Sumário

1. [Introdução](#introdução)
2. [Configuração do Projeto](#configuração-do-projeto)
   - [Pré-requisitos](#pré-requisitos)
   - [Configuração Inicial](#configuração-inicial)
3. [Scripts de Automação](#scripts-de-automação)
   - [Deploy](#deploy)
   - [Escalabilidade](#escalabilidade)
   - [Remoção de Serviços](#remoção-de-serviços)
   - [Monitoramento](#monitoramento)
4. [Pipeline de CI/CD](#pipeline-de-cicd)
5. [Testes de Desempenho](#testes-de-desempenho)
6. [Segurança do Cluster](#segurança-do-cluster)
7. [Desafios e Soluções](#desafios-e-soluções)
8. [Melhores Práticas](#melhores-práticas)

## Introdução

Este projeto configura um ambiente Docker Swarm completo com NGINX como balanceador de carga, um serviço de banco de dados PostgreSQL, e um pipeline de CI/CD usando GitHub Actions.

## Configuração do Projeto

### Pré-requisitos

- Docker e Docker Compose instalados
- Conta no Docker Hub
- Acesso a um servidor para o Docker Swarm (opcional para deploy remoto)

### Configuração Inicial

Clone o repositório e navegue até o diretório do projeto:

```bash
git clone https://github.com/privgabriel/PraticaDocker.git
cd PraticaDocker
