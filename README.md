# Spotify_Playlist

**Número da Lista**: 40<br>
**Conteúdo da Disciplina**: Final<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 16/0112028  |  André Goretti Motta |

## Sobre 
Este projeto visa reorganizar uma playlist do Spotify baseado em métricas fornecidas pelo próprio serviço, como tempo, "dançabilidade" e positividade das músicas. Desta forma, mesmo em playlists diversificadas, as músicas terão uma "vibe" mais coerente ao agrupar músicas semelhantes. Para isso, foi criado um grafo que calcula a distância entre as músicas com base nas variáveis mencionadas e o algoritmo "Traveling Salesperson Problem" é utilizado para agrupar as músicas de forma eficiente.

## Screenshots
Adicione 3 ou mais screenshots do projeto em funcionamento.

## Instalação 
**Linguagem**: Python3<br>
**Framework**: Jupyter Notebook<br>
Para rodar o projeto é nescessário ter o jupyter notebook instalado. Para isso rode os comandos com "pip"
>pip install notebook

instalar as bibliotecas:

>pip install python-tsp numpy

E depois rodar:

>jupyter notebook

## Uso 
Para utilizar o projeto, basta executar as células no Jupyter Notebook. <br/>
Para alterar a playlist a ser reorganizada, basta baixar o arquivo CSV (recomendo o uso do site [https://exportify.net](https://exportify.net)), colocá-lo na pasta do projeto e renomear a variável "filename" para o nome do arquivo.<br/>
É possível modificar os pesos de cada variável para personalizar a distância de acordo com suas preferências na variável "weights".

## Outros 
Ainda é necessário experimentar com os pesos das variáveis para obter um agrupamento de músicas mais satisfatório, lembrando que a escolha dos pesos é subjetiva.




