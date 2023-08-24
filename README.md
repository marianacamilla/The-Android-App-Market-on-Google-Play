# The Android App Market on Google Play

**pt**

Aplicativos móveis podem ser extremamente lucrativos e muitas vezes simples de criar. Eles estão por toda a parte. Tendo isso em mente, neste notebook fizemos uma análise de mercado de aplicativos Android, comparando mais de dez mil aplicativos na Google Play em diferentes categorias. 

note:
- app.csv: contém todos os detalhes das aplicações.
- user_reviews.csv: contém 100 reviews de cada app.

## Steps
### Task 1: Google Play Store apps and reviews
Importar o arquivo csv e remover aplicativos duplicados.

### Task 2: Data cleaning
Nome auto-descritivo, tirando caracteres especiais das colunas 'Install' e 'Price'.

### Task 3: Correcting data types
Corringindo o tipo das colunas 'Install' e 'Price'.

### Task 4: Exploring app categories:
Criando um gráfico para responder as perguntas:
- Qual categoria possui a maior participação de aplicativos (ativos) no mercado?
- Alguma categoria específica está dominando o mercado?
- Quais categorias têm o menor número de aplicativos?

### Task 5: Distribuition of app ratings
Verificando as avaliações dos apps e qual a média delas.

### Task 6: Size and price of an app
Criando gráficos para as questões:
- O tamanho de um aplicativo afeta sua avaliação?
- Os usuários realmente se importam com aplicativos pesados em termos de sistema ou preferem aplicativos leves?
- O preço de um aplicativo afeta sua avaliação?
- Os usuários sempre preferem aplicativos gratuitos em relação a aplicativos pagos?

### Task 7: Relation between app category and app price
Descobrindo a relação entre a categoria e preço, para definir que preço seria adequado ao aplicativo baseado em sua categoria.

### Task 8: Filter out "junk" apps
Os aplicativos mais caros são aplicativos "inúteis", então iremos filtrar esses aplicativos para refazer a visualização.

### Task 9: Popularity of paid apps vs free apps
Comparando a quantidade de downloads de apps pagos vs apps gratuitos.

### Task 10: Sentiment analysis of user reviews
Gráfico com reviews de usuários em apps pagos e apps gratuitos.


## Conclusão:
- Observamos que disparadamente a categoria "Family" é a que possui maior concentração de aplicativos, enquanto a "Beauty" possui a menor.
- Observamos que a maioria dos aplicativos possuem avaliação acima de 4 estrelas.
- Vemos que aplicativos gratuitos possuem mais avalições e com um rating mais alto.
- Aplicativos gratuitos são mais populars que pagos:<br>
	apps pagos: 1k dowloads median.<br>
	apps free: 100k dowloads median.<br>
- Aplicativos pagos e gratuitos possuem níveis semelhantes de elogios em avaliações.


---------------------

**en**

Mobile apps can be extremely profitable and often easy to create. They are everywhere. Keeping this in mind, in this notebook, we conducted a market analysis of Android apps, comparing over ten thousand apps on Google Play in different categories.

note:
- app.csv: contains all application details.
- user_reviews.csv: contains 100 reviews of each app.

## Steps
### Task 1: Google Play Store apps and reviews
Import the CSV file and remove duplicate apps.

### Task 2: Data cleaning
Self-explanatory name, removing special characters from the 'Install' and 'Price' columns.

### Task 3: Correcting data types
Correcting the data type of the 'Install' and 'Price' columns.

### Task 4: Exploring app categories
Creating a graph to answer the questions:
- Which category has the highest share of active apps in the market?
- Is any specific category dominating the market?
- Which categories have the lowest number of apps?

### Task 5: Distribution of app ratings
Checking app ratings and their average.

### Task 6: Size and price of an app
Creating graphs for the questions:
- Does an app's size affect its rating?
- Do users care about system-heavy apps or do they prefer lightweight apps?
- Does the price of an app affect its rating?
- Do users always prefer free apps over paid ones?

### Task 7: Relation between app category and app price
Discovering the relation between category and price to determine an appropriate price based on the app's category.

### Task 8: Filter out "junk" apps
The most expensive apps are "useless," so we'll filter them out to redo the visualization.

### Task 9: Popularity of paid apps vs free apps
Comparing the number of downloads between paid and free apps.

### Task 10: Sentiment analysis of user reviews
Graphing user reviews in paid and free apps.

## Conclusion:
- We observe that the "Family" category has a significantly higher concentration of apps, while "Beauty" has the least.
- Most apps have ratings above 4 stars.
- Free apps have more reviews and higher ratings.
- Free apps are more popular than paid apps:<br>
  paid apps: 1k downloads median.<br>
  free apps: 100k downloads median.<br>
- paid and free apps have similar levels of praise in reviews.
