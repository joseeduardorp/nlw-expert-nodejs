# Projeto NLW Expert - Sistema de Votação em Tempo Real

Este projeto foi desenvolvido durante o evento Next Level Week (NLW) Expert da Rocketseat, na trilha de Node.js. O objetivo do projeto é criar um sistema de votação em tempo real utilizando diversas tecnologias modernas, incluindo o design pattern Observer.

## Funcionalidades

- Sistema de votação em tempo real.
- Visualização dos resultados de votação em tempo real.
- Armazenamento seguro dos dados utilizando PostgreSQL e Prisma.
- Comunicação em tempo real entre cliente e servidor utilizando WebSocket com Fastify.
- Validação de dados utilizando Zod.
- Utilização do padrão de projeto Observer para notificar os clientes sobre atualizações nos resultados de votação.

## Tecnologias Utilizadas

- Node.js
- TypeScript
- Fastify
- PostgreSQL
- Prisma
- Redis
- WebSocket
- Zod

## Executando o Projeto

1. Clone este repositório para sua máquina local.
2. Certifique-se de ter o Docker e o Docker Compose instalados em sua máquina.
3. Execute o comando `docker-compose up -d` na raiz do projeto para iniciar os containers do PostgreSQL e Redis.
4. Execute `npm install` para instalar as dependências do projeto.
5. Configure as variáveis de ambiente necessárias, como as credenciais do banco de dados PostgreSQL e Redis.
6. Execute `npm run dev` para iniciar o servidor de desenvolvimento.
7. Faça requisições para o endereço `http://localhost:3333`.
