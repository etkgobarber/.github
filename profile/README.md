<p align="center">
  <img src="https://github.com/etkgobarber/.github/blob/main/assets/go-barber-logo-transparente.png" alt="GoBarber - Agendamento" width="420" />
</p>

<h3 align="center">
  Agendamento de serviços de barbearia de forma simples, rápida e sem complicação.
</h3>

<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-em%20desenvolvimento-orange" />
  <img alt="Licença" src="https://img.shields.io/badge/licen%C3%A7a-MIT-blue" />
  <img alt="Frontend" src="https://img.shields.io/badge/reposit%C3%B3rio-frontend-red" />
</p>

---

## 💈 Sobre o projeto

O **GoBarber** é uma plataforma de agendamento para barbearias. Ela conecta **clientes** e **barbeiros**: o cliente escolhe o profissional, o dia e o horário que preferir, e o barbeiro acompanha toda a sua agenda em um painel organizado.

Este repositório contém o **frontend (web)** da aplicação.

---

## 🎯 Principais funcionalidades

### 👤 Autenticação e conta
- Cadastro de novos usuários
- Login com e-mail e senha
- Recuperação e redefinição de senha por e-mail
- Atualização de perfil (nome, e-mail, senha e foto/avatar)

### ✂️ Para o cliente
- Listagem de barbeiros disponíveis
- Visualização de dias e horários livres de cada profissional
- Criação de agendamentos em poucos cliques
- Consulta dos próximos agendamentos

### 📅 Para o barbeiro
- Dashboard com a agenda do dia
- Calendário para navegar entre os dias do mês
- Separação dos horários entre manhã e tarde
- Destaque para o próximo atendimento
- Visualização dos dados e do avatar do cliente agendado

### 🔔 Experiência do usuário
- Notificações de feedback (sucesso e erro) em ações importantes
- Validação de formulários em tempo real
- Rotas protegidas para usuários autenticados
- Layout responsivo

---

## 🛠 Tecnologias previstas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Styled Components](https://styled-components.com/)
- [React Router](https://reactrouter.com/)
- [Axios](https://axios-http.com/)
- [Unform](https://unform.dev/) + [Yup](https://github.com/jquense/yup) (formulários e validação)
- [React Icons](https://react-icons.github.io/react-icons/)

> As tecnologias podem ser ajustadas conforme a evolução do projeto.

---

## 🗂 Repositórios da organização

| Repositório | Descrição |
| ----------- | --------- |
| `frontend` | Aplicação web (frontend) |
| `backend` | API REST (backend) |
| `gobarber-mobile` | Aplicativo mobile |

---

## 🚀 Como executar o frontend

```bash
# Clone o repositório
git clone https://github.com/etkgobarber/frontend.git

# Acesse a pasta do projeto
cd frontend

# Instale as dependências
yarn install   # ou npm install

# Inicie a aplicação
yarn start     # ou npm start
```

A aplicação ficará disponível em `http://localhost:3000`.

> ⚠️ É necessário ter a **API do GoBarber** em execução para que todas as funcionalidades funcionem corretamente.

---

## 🤝 Como contribuir

1. Faça um **fork** do projeto
2. Crie uma branch para a sua feature: `git checkout -b feature/minha-feature`
3. Faça o commit das alterações: `git commit -m "feat: minha nova feature"`
4. Envie para a sua branch: `git push origin feature/minha-feature`
5. Abra um **Pull Request**

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">
  Feito com 💈 pela equipe <strong>GoBarber</strong>
</p>
