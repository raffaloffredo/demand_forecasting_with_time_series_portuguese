# Análise de séries temporais para previsão de demanda

<img align="center" alt="EN" height="30" width="30" src="https://em-content.zobj.net/thumbs/120/whatsapp/326/flag-united-states_1f1fa-1f1f8.png"> _Click [here](https://github.com/raffaloffredo/demand_forecasting_with_time_series) to English-EN_   
<br/>

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgGjWV1o46xE2mjh41RmUr0jt_b6tn1vy8BK-JSH7Jze_rlWuSTsyX5tXHzHWekinfEStUdfBBwY7E5YAjcVK6FNbjWkJiZ-r7HF1EqRoB8QIp3RTFJqlG91tGB3cQoj8VH_pPv5t74ifO9CtzrOf3NDlzEHF56vy68FcqrRxI7bBJC51cX1n-5kOkCsyQ/s16000/clock-01.pngg" height=500px>
</p>
<br/>

## Sobre o projeto
Esse estudo teve por objetivo criar um modelo de _machine-learnin_ para prever a demanda por vinhos em uma loja especializada nesse produto. Foi utilizado o Pandas Profiling para gerar um relatório que auxiliou na análise exploratória dos dados. Também, foi aplicado _feature engineering_ que gerou 9 novos atributos. Com o teste Augumented Dickey Fuller (ADF) foi inferido que a série era não-estacionária e, por esse motivo, foi feita a transformação da série em estacionária com o uso das técnicas de aplicação de _log_ para redução da magnitude dos valores, subtração da média móvel de 30 períodos e a diferenciação. A previsão teve como parâmetro 120 dias e foram usados os seguintes métodos: abordagem Naive, Média Móvel, Holt's Linear Trend Model, ARIMA, Prophet e PyCaret. Sendo que nesse último foram gerados 27 modelos preliminares, do qual se selecionou o melhor para prosseguir com os ajustes de hiperparâmetros e previsão dos dados.

Como resultado, de acordo com o MAPE, o modelo gerado pelo ARIMA obteve o melhor desempenho, com uma taxa de erro de apenas 2.33%, seguido pelo Prophet com 2.87% e do Holt com 2.90%.

* **[Projeto na íntegra](https://github.com/raffaloffredo/demand_forecasting_with_time_series_portuguese/blob/main/%5BLoffredoDS%5D_Previs%C3%A3o_de_demanda_com_S%C3%A9ries_Temporais.ipynb)**
* **[Artigo](https://medium.com/@loffredo.ds/an%C3%A1lise-de-s%C3%A9ries-temporais-para-previs%C3%A3o-de-demanda-6978ea069914)**
* **[Artigo Resumido (Resultados)](https://www.linkedin.com/pulse/previs%25C3%25A3o-de-demanda-vinhos-por-meio-an%25C3%25A1lise-s%25C3%25A9ries-raffaela-loffredo)**

<br/>

## Material Extra
Os principais resultados obtidos foram condensados em um infográfico.

<p align="center">
  <img src="https://media.licdn.com/dms/image/D4D12AQGJvSmNMtxI0A/article-inline_image-shrink_1500_2232/0/1696940949355?e=1702512000&v=beta&t=OkMXeLL1ZgE6u4grXJ9-rZPGA3hwqsSJUtr1mLTPpf4" width="70%">
</p>

<br/>

## Outros projetos

* **[Classificação para identificar a saúde de um feto](https://github.com/raffaloffredo/fetus_health_classification_portuguese)**
* **[Previsão de Custo de Seguro de Vida](https://github.com/raffaloffredo/life_insurance_price_prediction_portuguese)**
* **[Previsão de Churn](https://github.com/raffaloffredo/churn_prediction_portuguese)**
* **[Detecção de fraude em cartão de crédito](https://github.com/raffaloffredo/fraud_detection_portuguese)**
* **[Airbnb New York](https://github.com/raffaloffredo/airbnb_new_york_portuguese)**
* **[Estudo atualizado sobre COVID-19 no Brasil e no mundo](https://github.com/raffaloffredo/covid_2023_portuguese)**
<br/>

 ## Contatos
<div>
  <a href="https://www.linkedin.com/in/raffaela-loffredo/?locale=en_US" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://sites.google.com/view/loffredo/" target="_blank"><img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white"></a>
  <a href = "mailto:raffaloffredo@protonmail.com"><img src="https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/loffredo.ds" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://medium.com/@loffredo.ds" target="_blank"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"></a>
</div>
