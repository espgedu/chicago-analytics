# Análise de Dados Públicos de Chicago 

## Visão Geral do Projeto

Este projeto acadêmico foca na análise de dados públicos da cidade de Chicago, explorando informações de censo populacional, criminalidade e desempenho de escolas públicas. Ele foi desenvolvido como parte do curso **"Databases and SQL for Data Science with Python" da IBM**. O objetivo principal é identificar padrões e correlações entre esses conjuntos de dados, buscando entender as dinâmicas sociais e urbanas de Chicago através da análise de indicadores socioeconômicos, taxas de criminalidade e a qualidade da educação.

![Imagem meramente ilustrativa](https://encrypted-tbn1.gstatic.com/licensed-image?q=tbn:ANd9GcSB0E2zhAxGdow-1Ca2cqbFayha0cISnpalJ8LOJNcEFdl6rVT56xCZlRl_T9oWbM1FmZarokjZ0gGiwSmaOmwTisil8TLCEv8AlRoZ9E9Ihchn-mg)

## Ferramentas Utilizadas

Para realizar esta análise, foram usados:

1. Jupyter Notebook: Ambiente interativo para desenvolvimento, execução e documentação do código Python e SQL.

2. Python: Linguagem de programação principal para manipulação, limpeza e análise de dados. Usamos bibliotecas como pandas, numpy, matplotlib e seaborn.

3. SQL (MySQL, SQLite): Sistemas de gerenciamento de banco de dados para armazenar e consultar os conjuntos de dados de forma eficiente. MySQL é usado para o banco de dados principal, e SQLite pode ser utilizado para prototipagem ou dados locais.

4. SQLAlchemy: Toolkit SQL e Mapeador Objeto-Relacional (ORM) para Python, facilitando a interação com os bancos de dados.

5. SQL Magic Module: Extensão do IPython que permite executar comandos SQL diretamente nas células do Jupyter Notebook.

6. Conectores Python para MySQL: Para facilitar a comunicação entre os notebooks Jupyter e o banco de dados MySQL.

## Estrutura do Projeto

├── .conda/                        # Pasta de ambiente Conda utilizado
├── DATA/                          # Pasta para dados 
├── FinalDB                        # Arquivo do banco de dados 
├── LICENSE                        # Arquivo de licença do projeto
├── mod5-final-project-v2.ipynb    # O principal e único Jupyter Notebook com a análise completa.
└── README.md                      # Este arquivo, com a descrição do projeto.