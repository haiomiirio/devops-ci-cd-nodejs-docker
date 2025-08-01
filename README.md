# DevOps CI/CD Node.js com Docker

Este é um projeto de exemplo de uma aplicação Node.js integrada com Docker e GitHub Actions para demonstrar um pipeline CI/CD automatizado.

## 🚀 Funcionalidades

- Aplicação Node.js simples com um servidor HTTP.
- Dockerfile para empacotamento da aplicação.
- Pipeline CI/CD com GitHub Actions.
- Publicação automática da imagem no Docker Hub.

## 📁 Estrutura

```bash
devops-ci-cd-nodejs-docker/
├── index.js
├── package.json
├── Dockerfile
├── .dockerignore
├── .github/
│   └── workflows/
│       └── docker-publish.yml
