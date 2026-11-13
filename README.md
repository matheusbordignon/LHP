## LHP
# 📝 Gerenciador de Tarefas

CLI simples em Python para gerenciar suas tarefas direto pelo terminal. Os dados ficam salvos em um arquivo JSON local, sem precisar de banco de dados ou bibliotecas externas.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Licença](https://img.shields.io/badge/licença-MIT-green)

## 📋 Sobre o projeto

Este projeto foi criado para praticar o fluxo completo do GitHub: commits, branches, issues e pull requests, ao mesmo tempo em que resulta em uma ferramenta útil para o dia a dia.

## ✅ Funcionalidades

- [x] Adicionar tarefa
- [x] Listar tarefas
- [ ] Concluir tarefa
- [ ] Remover tarefa

## ⚙️ Requisitos

- [Python 3.8](https://www.python.org/downloads/) ou superior
- [Git](https://git-scm.com/downloads)

## 🚀 Instalação

```bash
git clone https://github.com/SEU-USUARIO/gerenciador-de-tarefas.git
cd gerenciador-de-tarefas
```

Não há dependências para instalar.

## 💻 Como usar

**Adicionar uma tarefa:**

```bash
python tarefas.py adicionar "Estudar Git"
```

**Listar tarefas:**

```bash
python tarefas.py listar
```

Exemplo de saída:

```
1. [ ] Estudar Git
2. [✔] Fazer compras
```

**Concluir uma tarefa** *(em desenvolvimento)*:

```bash
python tarefas.py concluir 1
```

**Remover uma tarefa** *(em desenvolvimento)*:

```bash
python tarefas.py remover 1
```

## 📁 Estrutura do projeto

```
gerenciador-de-tarefas/
├── tarefas.py      # código principal
├── tarefas.json    # tarefas salvas (criado automaticamente)
└── README.md       # documentação
```

## 🤝 Como contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua alteração:
   ```bash
   git checkout -b feature/minha-melhoria
   ```
3. Faça o commit das suas mudanças:
   ```bash
   git commit -m "feat: descrição da melhoria"
   ```
4. Envie para o seu fork:
   ```bash
   git push origin feature/minha-melhoria
   ```
5. Abra um Pull Request

Sugestões e bugs podem ser registrados na aba [Issues](https://github.com/SEU-USUARIO/gerenciador-de-tarefas/issues).

## 🗺️ Próximos passos

- [ ] Testes automatizados
- [ ] Prioridade e data limite nas tarefas
- [ ] Adicionar `.gitignore` para o `tarefas.json`

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais informações.

## 👤 Autor

**Seu Nome**
GitHub: [@SEU-USUARIO](https://github.com/SEU-USUARIO)
