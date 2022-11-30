# MiniProjeto_1
## O que foi feito:
-  Importação de dados e Retirada de algumas métricas sobre a massa de dados.
-  Criação da coluna  “Value_per_ft” para descobrir o valor por fts de cada imóvel.
- Instalação da biblioteca “uszipcode”.
- Criação de vetor ‘cidades’ onde é feito um for  para o preenchimento desse vetor onde através do  campo ‘zipcode’ é identificado a cidade.
-Criação da coluna ‘city’ que é preenchida com o vetor ‘cidades’.
-Consultando quantidade de imóveis por cidade.
- Criação de df com a média por pés  agrupado por cidade.
- Criação de gráfico utilizando o Seaborn para melhor visualização dos dados.
-Criação de gráfico utilizando o DF principal para identificar o percentual de imóveis por cidade.
- Identificação de imóveis mais baratos e mais caros (tomando como base o valor por pés de cada imóvel).
- Identificação de duplicados para o cálculo do valor de revenda.
- Criação de lista com o os valores de venda por Id.
- Transformando a série criada em dataframe primeiramente só com a coluna price.
- Criação de outro df com um split da coluna ‘price’ do df anterior, resultando em 2 colunas
‘V1 ‘e ‘v2’.
-Junção das duas tabelas criadas e exclusão do campo ‘price’.
- Criação de coluna ‘resale’ com o a subtração da coluna ‘v1’ sobre ‘v2’ e ordenando o df por essa coluna.
- Com isso verificamos o imóvel que mais valorizou. (no caso o Id 6021500970)
