## 📊 Sistema de Gerenciamento para uma Cafeteria - Desenvolvido em SQLite
🔧 Desenvolvido por: Gustavo Lopes  


## 📑 Sumário 
1. ☕ Descrição do Projeto 

2. 🏗️ Estrutura do Banco de Dados 

3. 🔗 Relacionamentos 

4. 🔥 Funcionalidades Desenvolvidas 

5. 📊 Consultas Importantes 

6. 🚀 Melhorias Futuras 

7. 🧠 Como Executar o Projeto 

8. ✅ Conclusão 

 

  


## 1. ☕ Descrição do Projeto
Este projeto tem como objetivo desenvolver um banco de dados relacional para gerenciar as operações de uma cafeteria fictícia. O banco de dados foi construído utilizando SQLite, com foco em registrar informações sobre produtos, clientes, colaboradores, fornecedores, pedidos e itens dos pedidos. 

O projeto simula toda a operação de uma cafeteria, desde o cadastro de produtos e fornecedores, passando pela realização de pedidos pelos clientes, até o controle do faturamento diário. Além disso, foram implementadas consultas analíticas, views e triggers para automatizar e facilitar o gerenciamento da cafeteria. 

 
## 2. Estrutura do Banco de Dados Tabelas Criadas: 

☕ Produtos 

👥 Clientes 

🧾 Pedidos 

📦 ItensPedidos 

💼 Colaboradores 

🚚 Fornecedores 

💰 FaturamentoDiario 

 

## 3.🔗 Relacionamentos 

Um cliente pode realizar vários pedidos (1:N). 

Um pedido pode ter vários itens de pedidos (1:N). 

Cada item de pedido está ligado a um produto. 

Cada produto pode estar associado a um fornecedor. 

Cada pedido pode ser atendido por um colaborador. 

## 4.🔥 Funcionalidades Desenvolvidas 

️ Criação das tabelas com integridade referencial. 

 Inserção de dados completos. 

 Consultas SQL avançadas com JOINs, GROUP BY, HAVING, UNION e subconsultas. 

 Criação de Views como: ViewClientes, ViewValorTotalPedido, ViewItensPedidoDetalhado, ViewProdutosFornecedores, ViewEstoqueBaixo, ViewPedidosColaboradores. 

 Trigger para atualização automática do faturamento diário. 

 

## 5.📊 Consultas Importantes 

🔍 Clientes que fizeram pedidos em determinado mês. 

🔍 Clientes que não fizeram pedidos. 

📦 Produtos não vendidos. 

💸 Produtos acima da média de preço. 

💰 Faturamento diário total. 

📋 Itens detalhados dos pedidos. 

🔗 Relacionamento de produtos com fornecedores. 

👥 Pedidos associados aos colaboradores. 

 

## 6.🚀 Melhorias Futuras 

➕ Controle de estoque dinâmico. 

❌ Implementação de cancelamentos. 

🏷️ Sistema de promoções. 

📑 Relatórios de vendas por categoria. 

🗄️ Backup automático. 

 

## 7.🧠 Como Executar o Projeto 

Instale SQLite ou um gerenciador (SQLiteStudio, DB Browser). 

Execute os scripts na seguinte ordem: 

01-Criacao-Tabelas.sql 

02-Insercao-Dados.sql 

03-Consultas-Select-Join.sql 

04-Views.sql 

05-Triggers.sql 

06-Explore as consultas, views e triggers. 

 

## 8.✅ Conclusão
Este projeto foi desenvolvido para consolidar conhecimentos em banco de dados SQL, aplicando conceitos de modelagem relacional, integridade referencial, consultas complexas e automação de processos com views e triggers. O sistema simula de forma fiel as operações diárias de uma cafeteria moderna, desde o atendimento ao cliente até o controle financeiro e operacional. 

 
