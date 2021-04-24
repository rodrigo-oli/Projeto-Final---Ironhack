## Análise de aves no Brasil
![espécies_observadas](https://user-images.githubusercontent.com/42010810/115964661-f3440580-a4fb-11eb-9a85-dd2e6671cd60.gif)


# Objetivos:

•	Visualizar dados por mapa e linha do tempo
•	Indicar uma projeção de abundância das espécies
•	Qual a interferência do homem na análise abundância 

# Ferramentas:

•	Jupyter Notebook, Python, Panda e Tableau

# Fonte de dados:

•	 https://ebird.org/data/download 

# Tratamento de dados:

Utilização do Python para o tratamento de dados, o arquivo possui mais de 8 milhões de dados, mais de 1.700 espécies. São dados registrados de avistamento de aves dentro do território brasileiro desde 1961.
Foi realizado um tratamento para obter dados aprovados e excluir os reprovados e utilização somente dos dados necessários de (espécie, quantidade observada, data, latitude e longitude).

# Análise:

Foi utilizado o Tableau para a visualização dos dados por mapa e gráficos.

•	Todas os dados definidos com localização nome da espécie pela soma de observação de todos os anos: 

 ![image](https://user-images.githubusercontent.com/42010810/115964167-83348000-a4f9-11eb-9c23-2f6cf1869732.png)

•	Visualização da quantidade total de algumas espécies:

![espécies](https://user-images.githubusercontent.com/42010810/115964268-02c24f00-a4fa-11eb-87ca-68aa21b7a888.gif)

•	Analisando algumas espécies por período:

![image](https://user-images.githubusercontent.com/42010810/115964313-369d7480-a4fa-11eb-844a-1a6b59678ca3.png)

•	Analisando algumas espécies que obtiveram dados menor em 2017 do que em 2016:

![image](https://user-images.githubusercontent.com/42010810/115964531-51241d80-a4fb-11eb-94de-d6687f0ad5aa.png)

•	Quantidade e população observada:

![image](https://user-images.githubusercontent.com/42010810/115964605-b0822d80-a4fb-11eb-8f6c-657a25020be1.png)

•	Modelagem preditiva com suavização exponencial para os próximos anos:

![image](https://user-images.githubusercontent.com/42010810/115964617-bd9f1c80-a4fb-11eb-97b1-b821cd7f8a4d.png)


# Desafios:

Para melhor compreensão dos dados apresentados, um bom conhecimento de biologia e mais especificamente sobre Aves, pode influenciar na geração de insights e futuras conclusões, como não tenho conhecimento específico nessa área foi preciso pesquisar informações para entender o contexto desses animais. 
O tratamento e visualização de dados foi um tanto quanto desafiador pela alta quantidade de dados, mesmo observando e filtrando espécies específicas.

# Próximas Etapas:

Para as próximas etapas do projeto é preciso analisar os furacões por data, localização e também é preciso entender a mobilidade e migração dessas espécies analisadas e ter os dados de partida e chegada e quais de fato são seus destinos. 

