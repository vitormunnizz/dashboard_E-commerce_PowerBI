## Descrição do Projeto

Este projeto tem como objetivo desenvolver um **Painel Gerencial** no Power BI para um e-commerce, focado em melhorar a análise e a previsão de vendas. Com o auxílio de um **modelo de regressão linear**, o painel fornece previsões de faturamento e recomendações práticas para maximizar a performance de vendas. Através de visualizações e métricas detalhadas, o painel auxilia gestores a identificar oportunidades de crescimento e ajustar estratégias de marketing e vendas.

## Funcionalidades

- **Previsão de Faturamento**: Utiliza um modelo de regressão linear para projetar o faturamento futuro, ajudando a equipe a definir metas e estratégias.
- **Visualização de Indicadores de Vendas**: Análise de desempenho das vendas por diferentes métricas, como categoria de produto, data e estado.
- **Segmentação de Clientes e Canais**: Insights detalhados sobre o perfil dos clientes e os canais de vendas mais efetivos, permitindo segmentações por idade, localização e preferências de compra.
- **Análise Comparativa**: Comparação de preços com e sem frete e análise por bandeiras de cartão de crédito, para entender como esses fatores influenciam o comportamento de compra.
- **Filtros Interativos**: Segmentação e filtros por categoria, data e região, para que o usuário ajuste a visualização e obtenha uma análise personalizada.

## Estrutura do Painel

O dashboard gerencial está dividido em duas páginas, cada uma dedicada a aspectos específicos:

1. **Página 1: Visão Geral de Vendas**  
   - Principais KPIs de vendas e previsões de faturamento.
   - Segmentação por categorias, estados e períodos para facilitar a identificação de tendências.
   - Gráficos de desempenho dos canais de venda, exibindo as vendas por canal e por bandeira de cartão.

2. **Página 2: Perfil de Clientes e Análise de Canais**  
   - Distribuição dos clientes por idade, estado e cidade de nascimento.
   - Análise das preferências de compra com filtros por idade, localização e categoria do produto.
   - Visualização da quantidade de compras por departamento e frequência de uso de diferentes canais.

## Estrutura dos Dados

A base de dados contém as seguintes colunas principais:

- **idcompra**: Número de identificação da compra.
- **idcanalvenda**: Canal de venda onde a transação foi realizada.
- **bandeira**: Bandeira do cartão utilizado na compra.
- **Data**: Data em que a compra foi efetuada.
- **Preço**: Preço do produto comprado.
- **Preço_com_frete**: Valor total da compra incluindo o frete.
- **Nome_Departamento**: Departamento do produto comprado.
- **estado**: Estado em que a compra foi realizada.
- **cliente_Log**: ID único do cliente.
- **Idade**: Idade do cliente.
- **uf_nascimento**: Cidade de nascimento do cliente.

Esses dados são tratados e visualizados no Power BI para fornecer uma visão abrangente do desempenho do e-commerce.

## Tecnologias Utilizadas

- **Power BI**: Plataforma de business intelligence para criação do dashboard gerencial.
- **Microsoft Excel/Google Sheets**: Utilizados para manipulação prévia dos dados, se necessário.
- **XLSX**: Formatos dos arquivos de dados importados para o Power BI.

## Resultados Esperados

O painel gerencial visa oferecer uma visão completa sobre o desempenho das vendas e o comportamento dos clientes, possibilitando:

- **Melhor Tomada de Decisão**: A partir da previsão de vendas e das recomendações oferecidas, a equipe pode implementar estratégias para aumentar as vendas.
- **Identificação de Oportunidades de Crescimento**: Com a segmentação por categorias e análise de canais, é possível reconhecer áreas de oportunidade e investir nos segmentos mais lucrativos.
- **Otimização de Preços e Frete**: Análise dos preços com e sem frete para avaliar o impacto sobre a decisão de compra dos clientes.

## Autor

**Vitor Hugo Muniz de Sousa Santos**

Engenheiro de Computação | Cientista de Dados

[vitormunnizzdev@gmail.com](mailto:vitormunnizzdev@gmail.com)
[www.linkedin.com/in/vitormunnizz](https://www.linkedin.com/in/vitormunnizz)

## Licença

Este projeto está licenciado sob a **MIT License**.
Sinta-se livre para usar e modificar conforme necessário, mantendo os créditos ao autor.

**Se este projeto te ajudou, deixe uma estrela no repositório!**
