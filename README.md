# TechStore DB - Scripts e Stored Procedures

Este repositório contém a resolução das atividades práticas de Banco de Dados Relacional, focadas na implementação de **Consultas e Stored Procedures** no MySQL, utilizando o esquema fictício da loja `loja_tech`.

## O que você vai encontrar aqui?
- `setup_banco.sql`: Script original de criação das tabelas e carga inicial de dados (categorias, produtos, clientes, pedidos).
- `resolucao_consultas.sql`: Desafios de consultas (SELECTs, INNER JOINs e funções de agregação).
- `resolucao_procedures.sql`: Criação de 5 Stored Procedures essenciais abordando:
  - Procedimentos com retorno direto (Consultas)
  - Filtros dinâmicos via parâmetros `IN`
  - Manipulação de dados (`INSERT` e `UPDATE` seguros)
  - Extração de métricas com parâmetros de saída `OUT`

## Como executar
1. Abra o **MySQL Workbench** (ou SGBD de sua preferência).
2. Execute o arquivo de setup para criar a base `loja_tech`.
3. Certifique-se de usar o comando `USE loja_tech;`.
4. Execute os arquivos de resolução para criar as rotinas no banco.
5. Teste as procedures utilizando o comando `CALL nome_da_procedure(parametros);`.

## Aprendizados e Insights (Views vs Procedures)
Além das atividades práticas, este projeto consolida a diferença conceitual entre abstrações de banco. Descobrimos que enquanto **Stored Procedures** são as "receitas" para ações complexas e transacionais, **Views** são excelentes para:
1. Restringir acesso a dados sensíveis.
2. Facilitar o consumo por ferramentas de Business Intelligence (BI).
3. Encapsular junções (JOINs) massivas para consultas simplificadas.
4. Padronizar regras matemáticas de leitura de dados.
5. Integrar relatórios com frameworks ORM modernos.

---
*Atividade desenvolvida individualmente para a disciplina de Banco de Dados.*
