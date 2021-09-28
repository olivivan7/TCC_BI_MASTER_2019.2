# TCC-BI-MASTER-2019.2
Trabalho de Conclusão de Curso - BI Master : Sistemas Inteligentes de Apoio à Decisão


# ANÁLISE DE INVESTIMENTOS PARA CRIPTOMOEDAS (CRYPTO VALUATION): O PROJETO CARDANO [ADA]

#### Aluno: [Ivan Madeira de Oliveira](https://github.com/olivivan7)
#### Orientador: [Leonardo Alfredo Forero Mendoza](leofome@gmail.com)


---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão" - Turma 2019.2

---


### Agradecimentos

Gostaria de agradecer toda a minha família que me acompanhou durante toda essa jornada e aos professores do curso de pós-graduação em Business Intelligence: Sistemas Inteligentes de Apoio à Decisão em Negócios da PUC-Rio, em particular, meu orientador Dr. Leonardo Mendoza. 



### Resumo

A análise econômico financeira de investimentos é peça vital para a prosperidade de diversos empreendimentos. Sob essa ótica, o método tradicional do fluxo de caixa descontado e seus indicadores principais (valor presente líquido, taxa interna de retorno e tempo de retorno) tentam mensurar o retorno do projeto, enquanto o método CAPM (Capital Asset Pricing Model) é baseado nos valores esperados de rentabilidade e prêmio de risco. Ambos visam auxiliar na decisão de investir em um determinado projeto. 
No entanto, os projetos de criptomoedas não podem ser avaliados através do método tradicional por se comportarem como commodities, securities ou ações dependendo do projeto.
Desta forma, o presente trabalho, com foco na análise do Projeto Cardano e sua criptomoeda ADA, visa produzir um modelo de avaliação de investimentos para criptoativos ao apresentar: análise fundamentalista; análise técnica; análise quantitativa; análise de risco; projeções de preços e análise macroeconômica do mercado de criptoativos. Assim como, facilitar o entendimento e acesso ao mercado de criptomoedas.
Todas as metodologias foram usadas em sinergia para a tomada de decisão de investimento em projetos de criptomoedas.
Portanto, fora utilizado neste trabalho o Python como ferramenta para quantificar e qualificar os dados e valores de ativos sem fluxo de caixa, sob condições de incertezas e alta volatilidade.

Palavras chave: Bitcoin; Cardano; Ethereum; Criptomoedas; Blockchain; Decentralized Finance; Valuation; Fintech; Análise de Investimentos; Análise de Dados; Python para Finanças. 



### Abstract 

The economic financial analysis of investments is a vital part for the prosperity of many enterprises. From this perspective, the traditional discounted cash flow method and its main indicators (net present value, internal rate of return and time of return) try to measure the project's return, while the CAPM (Capital Asset Pricing Model) method is based on expected return values and risk premium. Both aim to assist in the decision to invest in a particular project.
However, Cryptocurrency projects cannot be valued using the traditional method as they behave like commodities, securities or stocks depending on the project.
Thus, the present work, focus on the analysis of the Cardano Project and its ADA Cryptocurrency, aims to produce an investment valuation model for Cryptoassets by handing over: fundamental analysis; technical analysis; quantitative analysis; risk analysis; price projections and macroeconomic analysis of the Cryptoassets market. As well as facilitating the understanding and access to the cryptocurrency market.
All methodologies were used in synergy for investment decision making in cryptocurrency projects.
Therefore, Python was used in this work as a tool to quantify and qualify the data and values of assets without cash flow, under conditions of uncertainty and high volatility.

Keywords: Bitcoin; Cardano; Ethereum; Cryptocurrencies; Blockchain; Decentralized Finance; Valuation; Fintech; Investment Analysis; Data Analysis; Python for Finance.



### 1. Introdução

1.1 Motivação

A motivação do presente trabalho é a necessidade de uma análise econômico financeira para investimentos em projetos de criptomoedas por serem ativos relativamente novos, volateis e, por possuirem uma nova tecnologia, muitos ainda não tiveram contato.

1.2 Objetivo

Com isso em vista, o objetivo desta monografia é construir uma base de conhecimentos que permeiam o mercado de criptomoedas para desmistificar tal classe de ativos.
Desta forma, a proposta deste trabalho é desenvolver um modelo de análise de investimentos para projetos de criptomoedas (“Crypto Valuation”) ao análisar, como base, o investimento no Projeto Cardano e sua criptomoeda ADA.

1.3 Descrição do Trabalho

O presente trabalho se presta a oferecer uma base de conhecimentos não somente históricos e teóricos, como também, práticos que possam ser aplicados na análise de investimentos de criptomoedas.
Fora utilizado o Python (parte prática) como ferramenta quantitativa e qualitativa na análise dos dados disponíveis até o momento.
Por fim, o trabalho faz uma projeção dos preços do Projeto Cardano [ADA] para possíveis valores em um período de dois anos.

1.4 Organização do Trabalho

Com tais objetivos em vista, o trabalho foi organizado em sete capítulos: Introdução; O Histórico do Mercado de Criptomoedas; O Projeto Cardano [ADA]: “Crypto 3.0”; Métodos utilizados na Avaliação de Investimentos em Criptomoedas; Modelagem das Opções Reais Utilizando Python (Parte 1 e Parte 2); Resultados (que apresentam todos os resultados advindos das análises); Conclusões e Sugestões de Investimento em Criptomoedas e Referências Bibliográficas.



### 2. Modelagem

Toda a avaliação foi feita utilizando Jupyter Notebook e a Linguagem de Programação Python.
	
Os métodos de avaliação foram os seguintes:

1.	Mineração dos dados;
2.	Análise exploratória dos dados;
3.	Análise quantitativa;
4.	Análise técnica e estudo das tendências do mercado de criptomoedas;
5.	Análise fundamentalista: avaliação econômica dos investimentos através de múltiplos do mercado; o modelo CAPM (Capital Asset Pricing Model); análise de risco; análise macroeconômica do mercado de criptomoedas através das plataformas Into The Block, Google Trends, Coinmarketcap e sites de notícias e artigos destinados ao mercado de criptomoedas;
6.	Modelos de previsão e estatística utilizando a biblioteca fbprophet;



### 3. Resultados

O conteúdo das análises, para quem tiver interesse, está nos arquivos “Parte 3 – Análise de Investimentos para Criptomoedas – O Projeto Cardano [ADA].ipynb” e no “Parte 4 – Análise de Investimentos para Criptomoedas – O Projeto Cardano [ADA].ipynb” e em PDF no arquivo “Parte 2 - Análise de Investimentos para Criptomoedas – O Projeto Cardano [ADA]: dados do Python.pdf”.


### 4. Conclusões

O Projeto Cardano liberou a Era Goguen e o acesso a Smart Contracts em seu Ecossistema em 12 de Agosto de 2021. Isso irá gerar um aumento considerável na demanda por parte das Instituições.  

Ainda há pela frente mais duas Eras para serem finalizadas e implementadas. 
A Era Basho, referente a Scaling, Optimization e Interoperability (Escalabilidade, Otimização e Interoperabilidade), também já foi parcialmente entregue, e a Era Voltaire, referente a Governança necessária para o ecossistema se tornar autosustentável.
Possui um equipe extremamente profissional e dedicada às propostas de melhoria de sua rede de Blockchain e vem provando sua capacidade entrega de tais atualizações e construção de novas parceriais e projetos ao redor do Mundo.

Como visto nas análises quantitativas, além de ser um projeto robusto, apresenta altas taxas de retorno sobre o investimento em médio e longo prazo.
Podemos notar que a Cardano foi a criptomoeda com maior retorno no período de 02/01/2019 até o momento com um ROI de 5127.97% de retorno. Superando até mesmo o retorno do portifólio fictício e o seu Índice Sortino de 1214.76%.
Enquanto o Bitcoin apresentou um retorno de 1074.53% para o mesmo período. O Ethereum apresentou 2045.62% para o mesmo período.
Sendo assim podemos concluir que vale a pena investir em criptomoedas a longo prazo.
Em relação a Cardano [ADA], apesar de ter apresentado períodos com índice sharpe negativo, conseguiu reverter tal tendência a partir de Julho de 2020 e, até mesmo, atingir um índice sharpe alto o suficiente para se equiparar ao Bitcoin, criptomoeda de referência do mercado, em meados de Março de 2021. Mantendo um índice maior do que 1 no presente momento.

Já na Simulação de Monte Carlo para Value at Risk e Conditional Value at Risk obteve valores ótimos em comparação aos possíveis ganhos no longo prazo.

Na avaliação por múltiplos, o projeto Cardano apresentou um Índice Preço/Lucro muito baixo que indica o negligenciamento do mercado em relação a tal projeto por ser relativamente novo, com um P/L igual a 0.02 .
Isso se dá pois ainda não ocerreu uma adoção amplamente disseminada por parte das pessoas físicas, portanto, uma [ÓTIMA] oportunidade de investimento com boas perspectivas de valorização.
Para fazer uma analogia com a Bolsa de Valores de São Paulo, os ativos listados no Ibovespa começaram 2020 com um P/L médio em torno de 16, antes da Pandemia.

Já o Market Cap Ratio é usado como parametro para possíveis projeções. A partir  das criptomoedas de referência do mercado é possível indicar o espaço de crescimento dos projetos que ainda não atingiram determinado valor de Market Cap.
Desta forma, podemos observar que [ADA/BTC] Market Cap Ratio está em 0.10 e [ADA/ETH] Market Cap Ratio está em 0.25. Logo, O Projeto Cardano, em comparação aos Projetos Dominantes, possui um grande potencial.
O Ethereum apresenta um [ETH/BTC] Market Cap Ratio de 0.24, assim, como a Cardano, também possui grande potencial.

O modelo CAPM (Capital Asset Pricing Model) previu um retorno esperado de 4,286.2%, porém, o projeto Cardano está, no momento desta redação, com um ROI de 5127.97% para o período analisado, de 02 de Janeiro de 2019 até os dias de hoje.

A modelagem do FBprophet nos permite visualizar rapidamente as previsões para uma série individual. Aqui, fizemos para o preço de fechamento em dólar da Cardano e o volume de transações.
Essas variáveis são importantes porque os analistas estão considerando o aumento do preço devido à facilidade dos indivíduos poderem negociar via robinhood e outras plataformas digitais em tempo real sem mediadores.
Além disso, a criptomoeda ADA é deflacionária uma vez que possuiu uma quantidade finita de tokens. De acordo com as previsões para cada série, pelo menos no futuro próximo, continuaremos a ver a Cardano aumentar de valor.

O projeto também oferece “fundos de investimentos” em suas carteiras digitais por ser um protocolo PoS (Proof of Stake) onde os usuários podem alocar suas ADA´s para produzirem mais criptomoedas ADA proporcionalmente a quantidade de moeda “estocada”.

Por fim, o Projeto Cardano, está se disseminando pelo mundo com muitos projetos em diversos país, tendo como um grande foco a África.

Atualmente, a Cardano é mais procurada no google do que o próprio Bitcoin. 


---

Matrícula: 192.110.191

https://github.com/olivivan7/TCC-BI-MASTER-2019.2

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*

---


