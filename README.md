# 🧑‍💻 Cursor Rules Package

Este repositório contém um conjunto completo de *regras para o Cursor AI Editor*, projetado para ajudar desenvolvedores a manter qualidade, consistência e segurança no dia a dia de desenvolvimento.

## 📦 O que inclui

- 📂 *.cursor/rules/* → Regras locais aplicadas ao projeto:
  - frontend.rule → Boas práticas para React/Next.js e frontend moderno.
  - backend.rule → Segurança e organização para backend (Node, Python, etc).
  - testing.rule → Princípios para testes e qualidade contínua.
  - debugging.rule → Como resolver bugs com disciplina.
  - quality.rule → Padrões de qualidade de código gerais.
  - github.rule → Fluxo de trabalho Git/GitHub moderno.
  - ai_safety.rule → Regras para reduzir alucinações do agente Cursor.

- 📄 *AGENTS.md*  
  Guia humano de boas práticas, descrevendo como o agente deve se comportar em frontend, backend, testes, debugging, GitHub e segurança contra alucinações.

- 🌍 *user-rules.yaml*  
  Regras globais para aplicar em todos os projetos do Cursor (configuradas em Settings > Rules).

---

## ⚙️ Como usar

### Instalar regras locais no projeto
1. Copie a pasta *.cursor/rules/* para a raiz do seu projeto.
2. O Cursor aplicará automaticamente essas regras sempre que você usar o agente ou o inline edit.

### Instalar regras globais
1. Vá em *Cursor → Settings → Rules*.
2. Importe ou copie o conteúdo de user-rules.yaml.
3. Essas regras passarão a valer para todos os projetos.

---

## 🚀 Fluxo de trabalho recomendado

- *Frontend* → Escreva componentes funcionais, use TypeScript estrito, lazy loading e mantenha nomes consistentes.  
- *Backend* → Valide inputs, proteja rotas, use logging seguro e mantenha serviços desacoplados.  
- *Testes* → Todo código novo precisa de testes; use CI/CD para garantir qualidade antes do merge.  
- *Debugging* → Reproduza o bug, escreva teste que falha, corrija a causa raiz, documente no PR.  
- *GitHub* → Trabalhe em feature branches, use Conventional Commits, PRs pequenos e revisados, CI obrigatório.  
- *IA (Cursor)* → Sempre baseado no código real, nunca inventar libs ou funções, pedir confirmação quando necessário.  

---

## 🛡️ Benefícios

- Redução de erros e inconsistências no time.  
- Menos alucinações da IA.  
- Código mais limpo, seguro e fácil de manter.  
- Fluxo GitHub moderno com CI/CD.  

---

## 📜 Licença

Uso livre para estudos e projetos. Adapte as regras conforme necessário para seu time.
