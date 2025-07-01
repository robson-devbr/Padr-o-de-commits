## 📄 README - Padrão de Commits no Projeto

### 🧠 Por que usar Commits Semânticos?

Usar mensagens de commit padronizadas ajuda a:

* Melhorar a leitura do histórico do Git
* Automatizar changelogs
* Facilitar revisão de código
* Colaborar melhor com equipes

---

## 🚀 Padrão: Conventional Commits

Use sempre o formato:

```bash
<tipo>(escopo opcional): mensagem clara no infinitivo
```

---

### ✅ Tipos mais comuns:

| Tipo       | Uso                                               | Exemplo                                            |
| ---------- | ------------------------------------------------- | -------------------------------------------------- |
| `feat`     | Nova funcionalidade ou recurso                    | `feat: adiciona login com Google`                  |
| `fix`      | Correção de bug                                   | `fix: corrige erro no botão de envio`              |
| `refactor` | Refatoração de código (sem mudar funcionalidade)  | `refactor: separa lógica de autenticação`          |
| `chore`    | Tarefas de manutenção (build, config, setup)      | `chore: atualiza dependências do projeto`          |
| `docs`     | Alterações em documentação                        | `docs: atualiza instruções no README`              |
| `test`     | Adição ou modificação de testes                   | `test: adiciona testes unitários para UserService` |
| `style`    | Mudança de estilo (espaços, ponto e vírgula etc.) | `style: ajusta indentação do código`               |
| `perf`     | Melhoria de performance                           | `perf: otimiza carregamento de imagens`            |
| `ci`       | Configuração de integração contínua               | `ci: configura GitHub Actions`                     |
| `build`    | Mudanças no sistema de build ou dependências      | `build: adiciona script de build com Webpack`      |

---

### ✍️ Boas práticas

* Escreva no **infinitivo**: `adiciona`, `corrige`, `atualiza`...
* Use **presente** e seja objetivo
* **Não use acentos** nos commits, se estiver padronizando para CI/CD
* Commits com mais de uma mudança → **quebre em vários**

---

### 🛠️ Exemplos reais

```bash
feat(auth): cria rota de login
fix(api): corrige status 500 na criação de usuário
docs: adiciona explicação de uso da API no README
refactor: extrai serviço de notificação para módulo separado
chore: instala dependência dotenv
```

---
