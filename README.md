# 📦 PriceTracker – Rastreador de preços da Amazon

O PriceTracker é uma plataforma completa de rastreamento de preços de produtos da Amazon.
Ela permite que usuários salvem produtos, recebam alertas quando os preços caem e obtenham recomendações inteligentes com base no histórico coletado.

O projeto tem como objetivo demonstrar domínio de arquitetura moderna, design modular, processamento assíncrono, filas, workers independentes e integração entre múltiplas tecnologias.
Partindo de um Modular Monolith e evoluindo, quando necessário, para microserviços.

## 🚀 Tecnologias Utilizadas
- Frontend
    * Next.js

- Backend
    * NestJS

- Infraestrutura
    * PostgreSQL – Banco de dados relacional
    * Redis – Cache e controle de rate-limit
    * Docker - Gerenciamento de conteiners

## 📘 Descrição Geral

O PriceTracker possibilita:

1. Cadastro de produtos da Amazon a partir da URL
2. Atualização periódica de preços via scraping
3. Registro do histórico de preços
4. Sugestões de preço baseadas em IA
5. Definição de preço desejado pelo usuário
6. Envio de notificações automáticas via Telegram
7. Painel simples e responsivo para gerenciamento dos produtos
8. Arquitetura baseada em módulos isolados para garantir evolução limpa e sustentável
