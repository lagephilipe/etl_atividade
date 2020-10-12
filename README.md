# ETL Projeto GoToData

Philipe Lage

# Dados

Os dados foram disponibilizados em csv e json, as tabelas analisadas em formato csv são "address" e "people", a tabela analisada em json é a "cars". Os dados estao contidos na pasta "bases" do projeto etl.

# ETL

Foi gerado um "Data Frame" de cada tabela a ser analisada. após a inserção foi realizada a combinação das 3 tabelas levando em conta o campo "id_people" que seria comum entre as três tabelas. Após realizado o processo foi realizado a substituição dos valores faltantes (NaN) por "none", para gerar dessa forma o arquivo final contendo as informações, a tabela final fica disponibilizada na pasta "saida_dados"

# LOAD

O Mysql foi utilizado para a carga de dados, onde de acordo com o código proposto  e realizada a inserção dos dados na tabela people.
