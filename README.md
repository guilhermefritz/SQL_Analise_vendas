
Link do projeto no Databricks :https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1686290630198130/3768819816422607/2524726961790864/latest.html

---------------------------------------------------------------------------------------------------------------------------


 
### Este projeto foi fundamentado a partir de uma análise descritiva dos dados históricos em cima de dados de vendas de uma loja global, abrangendo o período de 2016 a 2018. Utilizando a linguagem SQL no ambiente de desenvolvimento em nuvem Databricks, foi possível extrair insights relevantes que embasaram a compreensão do desempenho comercial e os principais fatores que impactaram o faturamento ao longo dos anos.

Os dados contêm informações das datas de vendas,nomes do compradores, categorias,sub categorias,segmentos,paises,regiões, produtos vendidos ,valores das vendas e outros campos.

#### O projeto envolve os seguintes elementos SQL:

####   -Filtros (WHERE)

####   -Agrupamento (GROUP BY)

####   -Ordenação (ORDER BY)

####   -Funções de Agregação(COUNT,SUM,AVG,MIN,MAX)

####   -Funções de manipulação de DATA no databricks

####  -Utilização de Condicionais (CASE WHEN)

####   -Utilização de Subconsultas 


## Perguntas do questionário:
#### 1-Qual foi a quantidade de pedidos no total?
#### 2-Qual foi o valor máximo de um pedido e o valor mínimo de um pedido entre todos os pedidos?
#### 3-De 2016 a 2018,quais foram os produtos TOP1(Lideraram o ranking) em valor de vendas de cada ano?
#### 4-Qual foi o semestre dos anos de 2017 e 2018 que obteve o maior faturamento ? Nesse determinado semestre quais foram os TOP2 produtos em vendas?
#### 5-Quais foram os estados que tiveram faturamento >70.000? E qual foi o Estado campeão?
#### 6-Desse determinado estado,quais foram as TOP3 cidades campeãs de vendas ?
#### 7-Qual foi a media de valor de venda agrupando por estado e cidade?
#### 8-As categorias de produtos sao divididas entre quais tipos ?
#### 9-Quanto cada categoria vendeu nos TOP3 estados?
#### 10-Supondo que (Tecnologia) é a categoria dominante em valor de vendas, teve algum ano em que outra categoria a sobressaiu?
#### 11-Da categoria de (Tecnologia) ,qual das sub-categorias se sobressaiu das demais?Dessa categoria quantos clientes eram distintos?
#### 12-Qual foi o tipo vencedor do ship mode(modo de envio) mais preferido pelos clientes
#### 13 -Qual foi o produto que mais faturou no decorrer dos anos?
#### 14-Veja a lista de compradores desse produto e o respectivo codigo postal de cada um .
#### 15-Teve algum ano em que no mês de Novembro a quantidade de faturamento foi superior que o mês de Dezembro?
#### 16-Quais foram os TOP3 clientes que mais gastaram na loja ?
