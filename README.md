# 🏋️ Sistema de Gestão de Treinos e Metas (Terminal)

Este é um projeto prático desenvolvido colaborativamente em Python para a disciplina de **Fundamentos da Programação** do curso Segurança da informação.

## 🎯 Sobre o Projeto
O sistema funciona via interface de linha de comando (CLI) e simula a gestão de treinos de um box de Cross-Training ou Academia. Ele permite que os usuários criem perfis protegidos por código de acesso e façam o acompanhamento local de seus resultados, treinos diários e metas físicas.

O diferencial do projeto é o sistema de **persistência de dados local**, que utiliza arquivos de texto dinâmicos para atuar como um banco de dados leve.

## ⚙️ Funcionalidades Principais
* **Sistema de Autenticação:** Criação de perfis de usuário, validação de credenciais e geração de arquivos de registro únicos por pessoa (ex: `registros_nome_sobrenome.txt`).
* **Gestão de Treinos (CRUD):** Lançamento, edição, exclusão e visualização de registros com suporte a modalidades específicas (AMRAP, EMOM, For Time).
* **Filtros de Busca:** Pesquisa inteligente de treinos filtrando por modalidade ou movimentos específicos.
* **Acompanhamento de Metas:** Definição de objetivos (Bater PR, Emagrecimento, Hipertrofia) com uma função customizada de cálculo de datas para informar quantos dias faltam para a conclusão.

## 🛠️ Tecnologias e Arquitetura de Código
* **Linguagem:** Python
* **Conceitos de Engenharia de Software Aplicados:**
  * **Manipulação de Arquivos (File I/O):** Leitura, gravação, edição e exclusão automatizada de arquivos `.txt`.
  * **Tratamento de Exceções:** Prevenção de quebras de sistema através de blocos `try/except` (capturando `ValueError`, `FileNotFoundError`, etc).
  * **Validação de Inputs:** Implementação de funções de validação customizadas (ex: bloqueio de números em campos de texto usando iterações `isalpha()`).
  * **Modularização:** Separação de fluxos complexos em funções específicas para garantir a manutenibilidade do código.

> *Nota: Projeto construído com foco puramente acadêmico em lógica condicional estruturada e estabilidade de execução.*
