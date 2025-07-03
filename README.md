# Projeto CI/CD Demo

Este é um projeto simples para demonstrar uma pipeline de CI com GitHub Actions.

## Como testar

1. Clona o repositório
2. Instala dependências com `npm install`
3. Corre os testes com `npm test`

## Pipeline GitHub Actions

A pipeline é definida em `.github/workflows/ci.yml` e é executada automaticamente em cada `push`.

### Passos da pipeline:

- ✅ Fazer checkout do código
- 📦 Instalar dependências
- 🧪 Correr testes
- 🚀 Simular deploy (com `echo`)
