# Projeto-Integrador-III

### Crimes em Atlanta 2009-2017
Uma recolha de dados criminais a partir do portal de dados aberto do Departamento de Polícia de Atlanta. A sua ligação para descarregar o conjunto total de dados foi desactivada durante algum tempo. Trata-se de uma agregação de dados de toda a cidade para cada mês entre Janeiro de 2009 e Fevereiro de 2017
[Link do data.world](https://data.world/bryantahb/crime-in-atlanta-2009-2017)


| Coluna | Significado |
|--|--|
| crime | Categoria do crime |
| number | O número da ocorrência |
| date | Data da ocorrência |
| location | O endereço onde o crime aconteceu |
| beat | Delegacia/distrido policial que registrou a ocorrência |
| neighborhood | O bairro onde o crime aconteceu |
| npu | agrupamento de bairros, zoneamento/municípios |
| lat | Latitude |
| long | Longitude |


### Preparação ambiente
1. Baixe o arquivo fonte de dados no [data.world](https://data.world/bryantahb/crime-in-atlanta-2009-2017)
1. Rode o script de [tratamento de dados](tratamento-banco.ipynb), no Jupyter Notebook, na mesma pasta onde está o arquivo fonte
1. Foi utilizado o DB Browser para receber o database.db gerado no script de tratamentos acima, para baixar o DB Browser utilize o link - [db browser](https://sqlitebrowser.org/dl/)

### Bibliotecas 

para instalar as dependencias execute o comando: `pip install -r requirements.txt`
[requirements.txt](requirements.txt)


