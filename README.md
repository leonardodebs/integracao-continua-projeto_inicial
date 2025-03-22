# 🚀 Integração Contínua - Projeto Inicial

## 📌 Sobre o Projeto
Este projeto tem como objetivo implementar um fluxo de **Integração Contínua (CI)** utilizando ferramentas modernas para automação de builds, testes e deploys.

## 🛠 Tecnologias Utilizadas
- **GitHub Actions** - Automação de workflows CI/CD
- **Docker** - Containerização
- **Jenkins** (opcional) - Automação de pipeline
- **AWS** - Deploy em nuvem
- **Linux** - Comandos para automação e configuração

## 📂 Estrutura do Projeto
```
📦 integracao-continua-projeto_inicial
├── 📁 src               # Código-fonte
├── 📁 tests             # Testes automatizados
├── 📁 .github/workflows # Pipelines de CI/CD
├── Dockerfile           # Configuração do Docker
├── README.md            # Documentação do projeto
└── .gitignore           # Arquivos ignorados pelo Git
```

## 🚀 Como Executar o Projeto
### 🔧 Pré-requisitos
Antes de começar, certifique-se de ter instalado:
- [Git](https://git-scm.com/)
- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/) (se aplicável)
- [AWS CLI](https://aws.amazon.com/cli/) (se aplicável)

### 📥 Clonando o Repositório
```sh
git clone https://github.com/leonardodebs/integracao-continua-projeto_inicial.git
cd integracao-continua-projeto_inicial
```

### 🐳 Construindo a Imagem Docker
```sh
docker build -t meu-projeto-ci .
```

### ▶️ Rodando a Aplicação
```sh
docker run -p 3000:3000 meu-projeto-ci
```

### ✅ Executando os Testes
```sh
npm test  # Ou o comando correspondente à stack utilizada
```

## 🛠 Configuração do GitHub Actions
O projeto já possui um workflow pré-configurado em `.github/workflows/ci.yml`. Para ativá-lo:
1. Vá até **Actions** no repositório do GitHub.
2. Verifique se os workflows foram ativados corretamente.
3. A cada `push` ou `pull request`, o pipeline será executado automaticamente.

## 📜 Licença
Este projeto está licenciado sob a **MIT License** - 

---
💡 *Contribuições são bem-vindas! Sinta-se à vontade para abrir um PR ou relatar problemas.* 🚀
