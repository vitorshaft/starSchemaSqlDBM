# starSchemaSqlDBM
# Desafio de Integração e Modelagem de Dados com SQLDBM e MySQL

Este repositório contém o projeto de modelagem de dados de uma universidade, utilizando o SQLDBM para criação do diagrama entidade-relacionamento e MySQL como sistema de gerenciamento de banco de dados.

## Estrutura do Projeto

- **Professor**: Dados dos professores.
- **Departamento**: Detalhes sobre os departamentos, incluindo o professor coordenador.
- **Curso**: Dados dos cursos e sua relação com os departamentos.
- **Disciplina**: Informações sobre as disciplinas ministradas e o professor responsável.
- **Aluno** e **Matrícula**: Informações sobre os alunos e em quais disciplinas estão matriculados.
- **Pré-requisitos das Disciplinas**: Tabela para controlar os pré-requisitos acadêmicos entre disciplinas.

## Modelo de Dados e Relacionamentos

- O modelo foi estruturado em formato estrela (star schema) para otimizar as consultas analíticas.
- Foram criadas junções entre tabelas principais, como `Professor` e `Departamento`, `Disciplina` e `Curso`, formando um esquema que permite diversas análises relacionadas à estrutura universitária e às matrículas dos alunos.

## Principais Análises

- Contagem de alunos por curso e departamento.
- Relação entre professores e suas disciplinas.
- Análise de disciplinas com pré-requisitos.

## Conclusão

O projeto permitiu estruturar e organizar os dados da universidade em um modelo que facilita consultas analíticas, possibilitando a visualização de informações complexas sobre cursos, matrículas de alunos e a distribuição dos professores entre os departamentos.
