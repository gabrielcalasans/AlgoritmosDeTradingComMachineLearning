# Algoritmos de Trading com _Machine Learning_

Nesse curso foram abordadas características das negociações de ativos buscando suporte em algoritmos de _machine learning_ com python. Nesse repositório estão minhas anotações sobre as aulas e _scripts_ desenvolvidos. Abaixo segue uma breve descrição dos módulos do curso.

## Módulo 1 - Introdução a Aquisição de Dados, Retornos e Volatilidade

No módulo mais básico, o conteúdo exposto foi a aquisição de dados financeiros por meio do _Yahooo Finance_ e, além disso, tópicos básicos como o cálculo de retorno e volatilidade foram trabalhados, assim como o índice Sharpe.

## Módulo 2 - Análise Técnica

Breve introdução a análise técnica foi feita, abordando a interpretação e construção do gráfico de **_candlesticks_** por meio do python, padrões básicos de análise gráfica e indicadores técnicos. Ainda sobre os indicadores, os que receberam maior destaque foram:
- Médias móveis;
- Bandas de Bollinger;
- Níveis de suporte e resistência;
- RSI.
  
Além da parte teórica, nesse módulo também tive a oportunidade de criar o meu **primeiro algoritmo** de negociação que foi baseado nas médias móveis de 5 e 20 dias, com os algoritmos conhecidos como **_Golden/Death Cross_**.

## Módulo 3 - _Backtest_, Avaliação de Algoritmos

Nesta seção a análise do algoritmo foi trabalhada. 

Itens como a criação dos sinais de decisão (compra, venda ou espera) foram desenvolvidas, tal como a compreensão da importância e aplicação dos conceitos de **_take profit_** e **_stop loss_**.

Por ultimo, o módulo encerra com o desenvolvimento de um algoritmo para realizar o **_backtesting_** dos scripts de negociação baseando-se no investimento hipotético de um valor x, sujeito às condições de variação do preço com determinado _take profit_ e _stop loss_. Para mais, a comparação entre o desempenho do algoritmo com diferentes ativos também foi realizada.

## Módulo 4 - Trading com Algoritmos de _Machine Learning_ 

Em um primeiro momento, a definição de _Machine Learning (ML)_ foi apresentada, no qual foi feita a distinção entre os aprendizados supervisionados e não supervisionados, sempre os relacionando com sua aplicação dentro do mundo de finanças e também sua aplicação:
- Supervisionado
  - Classificação: decisão sobre compra ou venda;
  - Regressão: previsão de preços;

- Não supervisionado
  - Clustering: análise de características de grupos e setores;
  - Redução: identificação das variáveis mais relevantes na avaliação de algum ativo.
 
Apesar dessa breve introdução, o módulo focou principalmente nos algoritmos de **classificação** e os principais testados foram:
- SVM - _Support Vector Machine_;
- Árvore de Decisão: Básica;
- Árvore de Decisão: _Random Forest_
- Redes Neurais: Modelo MLPC de 64 e 32 camadas.

Além disso, outros indicadores foram apresentados, como o ATR - _Average True Range_ e _Williams Range_, assim como a "normalização" das médias móveis (processo necessário para tratar os dados antes de _inputa-los_ em um algoritmo de ML.

Ainda sobre esse módulo, foram apresentadas e desenvolvidas métricas para a avaliação dos algoritmos de ML, como a medida de **acurácia**, **matriz de confusão**, **curva ROC** e **AUC** - _Area Under Curve_.

Por último, o _backtest_ desenvolvido no módulo anterior foi utilizado para validar a eficácia os modelos de ML e próximos passos para continuar os estudos sobre a aplicação de ML no campo de finanças foram apresentados, como otimização dos parâmetros, alimentação dos dados por meio da avaliação conjunta de ativos.


**Certificado**: _https://www.coursera.org/account/accomplishments/certificate/ETH7XYEXN2J5_

    
