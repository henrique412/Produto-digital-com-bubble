# 📋 Task Manager — Gestão Inteligente de Tarefas (Bubble.io)

Um aplicativo web responsivo e seguro desenvolvido na plataforma **Bubble.io** para organização pessoal e de equipe. O sistema permite criar, categorizar e gerenciar tarefas em tempo real, contando com autenticação completa de usuários e isolamento de dados por conta.

---

## 💡 Sobre o Projeto

O **Task Manager** foi projetado para resolver o problema da descentralização de informações e falta de priorização de atividades no dia a dia. A solução foca em simplicidade, usabilidade e alta segurança.

### Principais Funcionalidades:
* **Autenticação de Usuários:** Cadastro de conta (*Sign Up*), login (*Log In*) e encerramento de sessão (*Log Out*).
* **Isolamento de Dados (Privacidade):** Regras no servidor (*Privacy Rules*) garantem que cada usuário visualize exclusivamente seus próprios projetos e tarefas.
* **Gestão de Tarefas (CRUD):** Criação e visualização de tarefas com campos dinâmicos (Nome, Descrição, Data, Status e Prioridade via *Option Sets*).
* **Interface Dinâmica e Responsiva:** Uso de elementos reutilizáveis no topo da página (*Header*) com alternância condicional de botões de acerto e modais integrados.

---

## 🚀 Como Acessar e Testar

Para avaliar a aplicação em funcionamento ou inspecionar sua estrutura no editor do Bubble, utilize as credenciais e links fornecidos abaixo:

### 1. Links de Acesso
* **Link da Aplicação (Preview/Teste):** [Acessar o App](https://henriquekadoguti.bubbleapps.io/version-test?debug_mode=true)
* **Link do Editor (Read-Only):** [Visualizar a Estrutura no Bubble](https://bubble.io/page?id=henriquekadoguti)

### 2. Credenciais para Teste Rápido
Você pode cadastrar uma nova conta diretamente na tela inicial ou utilizar o usuário de teste pré-configurado:

| E-mail | Senha |
| :--- | :--- |
| `teste@faculdade.com` | `123456` |

---

## 🛠️ Tecnologias Utilizadas

* **Plataforma No-Code:** [Bubble.io](https://bubble.io) (Full-stack web application builder).
* **Banco de Dados Relacional Nativo:**
  * **Data Types:** `User` (Usuários), `Task` (Tarefas).
  * **Option Sets:** `Status` (*Backlog*, *To Do*, *In Progress*, *Done*) e `Priority` (*Low*, *Medium*, *High*).
* **Segurança e Privacidade:** *Privacy Rules* baseadas em `This Task's Created By is Current User`.
* **Design & Layout:** Responsivo (Flexbox layout engine do Bubble), *Reusable Elements* e *Modals/Popups*.

---

## 🖼️ Capturas de Tela

*(Substitua os links dos marcadores abaixo pelos prints reais do seu aplicativo)*

### Tela Inicial e Autenticação
![Tela de Autenticação/Dashboard](https://via.placeholder.com/800x400?text=Preview+do+Dashboard+e+Login)

### Modal de Criação de Tarefa
![Modal de Nova Tarefa](https://via.placeholder.com/800x400?text=Popup+de+Criacao+de+Tarefa)

---

## 👥 Autor
Desenvolvido por **Henrique Kadoguti** como projeto acadêmico de desenvolvimento web sem código (*No-Code*).
