# BarberShop Management System

Um sistema completo de gerenciamento para barbearias, desenvolvido com React e Node.js.

![BarberShop Management System](.github/screenshots/dashboard.png)

## Visão Geral

O BarberShop Management System é um aplicativo web completo que permite aos proprietários de barbearias gerenciar todos os aspectos de seu negócio, incluindo:

- Gerenciamento de barbeiros e funcionários
- Cadastro e manutenção de clientes
- Agendamento de serviços
- Controle de estoque de produtos
- Registro de vendas e faturamento
- Relatórios e análises de desempenho

## Tecnologias Utilizadas

### Frontend
- React
- TypeScript
- TanStack Query (React Query)
- Tailwind CSS
- Shadcn UI
- Recharts para visualização de dados

### Backend
- Node.js
- Express
- TypeScript
- In-memory storage (implementação de referência)

## Estrutura do Projeto

O projeto está organizado em uma estrutura monorepo:

```
/
├── client/         # Frontend React
├── server/         # Backend Express
└── shared/         # Tipos e esquemas compartilhados
```

Para informações detalhadas sobre cada parte do sistema:

- [Documentação do Frontend](./docs/FRONTEND.md)
- [Documentação do Backend](./docs/BACKEND.md)
- [Guia de Implantação](./docs/DEPLOYMENT.md)

## Instalação e Execução

### Pré-requisitos
- Node.js 16+
- npm ou yarn

### Passos para Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/barbershop-management.git
cd barbershop-management
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o aplicativo em modo de desenvolvimento:
```bash
npm run dev
```

4. Acesse o aplicativo em `http://localhost:5000`

## Funcionalidades Principais

### Dashboard
- Visão geral do desempenho diário
- Métricas de agendamentos e vendas
- Análise de desempenho dos barbeiros

### Agendamentos
- Cadastro e gerenciamento de horários
- Visualização de agenda diária/semanal/mensal
- Atribuição de barbeiros e serviços

### Clientes
- Cadastro e manutenção de dados dos clientes
- Histórico de serviços e compras
- Preferências e observações

### Barbeiros
- Registro de profissionais
- Controle de disponibilidade
- Análise de produtividade

### Serviços
- Cadastro de serviços oferecidos
- Definição de preços e duração
- Categorização por tipo

### Produtos
- Controle de estoque
- Registro de entradas e saídas
- Alertas de baixo estoque

### Vendas
- Registro de vendas de produtos e serviços
- Histórico de transações
- Relatórios de vendas

### Relatórios
- Análises financeiras
- Desempenho por período
- Exportação de dados

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE)

## Contato

Para sugestões, dúvidas ou contribuições, entre em contato através do [GitHub Issues](https://github.com/seu-usuario/barbershop-management/issues).