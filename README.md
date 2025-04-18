# Data Science Studies

A Ciência da Computação, com foco em Machine Learning, permite criar sistemas que aprendem com dados, identificam padrões e tomam decisões. Essa área impulsiona inovações em diversos setores, como saúde, finanças e tecnologia, tornando as soluções mais inteligentes e eficientes.

**Python** e **R**


## Tools
- [MNIST DATABASE](https://en.wikipedia.org/wiki/MNIST_database)
- [JAVA SE JDK x64 for H2O lib](https://www.oracle.com/java/technologies/downloads/#jdk21-windows)
- [Calculadora Covariância](https://mathcracker.com/pt/calculadora-covariancia)
- [Graphviz Viewer](https://dreampuf.github.io/GraphvizOnline/)
- [Skfuzzy 'imp' module error](https://github.com/scikit-fuzzy/scikit-fuzzy/commit/6c38e01451dedfbb49160d0d59a73a8f69d24c4e)
- [Python Igraph](https://igraph.org/python/tutorial/0.9.6/visualisation.html)
- [AI Community](https://huggingface.co/)


# Pesquisa


## 1. Banco de Dados

### Mongo DB

MongoDB é um banco de dados NoSQL, orientado a documentos, que armazena dados em formato JSON-like (BSON). Ele é altamente escalável, flexível e ideal para grandes volumes de dados não estruturados. Permite consultas rápidas e pode ser usado para aplicações web, móveis e big data.

- [Python](/mongo_db/py_integration.ipynb)
- [R](/mongo_db/r_integration.ipynb)

### PostgreSQL

PostgreSQL é um sistema de gerenciamento de banco de dados relacional (SGBDR) de código aberto, conhecido por sua robustez e conformidade com padrões SQL. Suporta consultas complexas, transações ACID, extensões e trabalha bem com grandes volumes de dados. É amplamente utilizado em aplicações empresariais e acadêmicas.

- [Python](/postgreSQL/py_integration.ipynb)
- [R](/postgreSQL/r_integration.ipynb)


## 2. Tratamento de Dados

O tratamento de dados envolve limpar, transformar e preparar os dados para análise. Inclui etapas como remoção de duplicatas, preenchimento de valores ausentes, correção de erros e normalização. É essencial para garantir a qualidade e a confiabilidade das análises e modelos preditivos.

- [Python](/python_data_science/tratamento_dados/primeiros_testes.ipynb)
- [R](/r_data_science/analise_trato_dados.ipynb)


## 3. Gráficos

***Python***

- [Disperção](/python_data_science/graficos_dashboards/dispersao.ipynb)  
O gráfico de dispersão mostra a relação entre duas variáveis numéricas. Cada ponto representa um par de valores, permitindo visualizar padrões, tendências e possíveis correlações entre os dados. É útil para análises exploratórias e identificação de outliers.

***R***

- [Setor, Spray e Boxplot](/r_data_science/graficos2.ipynb)  
**Gráfico de Setores:** também chamado de pizza, mostra proporções de um todo em fatias, ideal para comparar partes de um total.  
**Gráfico Spray:** exibe pontos dispersos em categorias, útil para ver concentração e variação.  
**Boxplot:** resume dados com mediana, quartis e outliers, ideal para comparar distribuições.


## 4. Estatística

***Python***

- [Amostra Estratificada](/python_data_science/estatistica1/amostra_estratificada.ipynb)  
A amostra estratificada é um tipo de amostragem em que a população é dividida em grupos (estratos) com características semelhantes. Em seguida, são selecionadas amostras de cada grupo, proporcionalmente ou igualmente, para garantir representatividade.

- [Anova Tukey](/python_data_science/estatistica2/anova_tukey.ipynb)  
A ANOVA Tukey é um teste estatístico usado após a ANOVA quando se identifica diferença entre grupos. Ele compara todas as médias duas a duas para saber exatamente quais grupos diferem entre si, controlando o erro tipo I nas comparações múltiplas.

***R***

- [Centrabilidade e Variabilidade](/r_data_science/estatistica/centralidade_variablidade.ipynb)  
Centrabilidade indica onde os dados se concentram, usando medidas como média, mediana e moda. Variabilidade mostra o grau de dispersão dos dados, com medidas como amplitude, variância e desvio padrão. Juntas, ajudam a entender o comportamento de um conjunto de dados.


## 5. Séries Temporais

***Python***

- [ARIMA](/python_data_science/series_temporais/previsao_arima.ipynb)  
ARIMA (AutoRegressive Integrated Moving Average) é um modelo usado para análise e previsão de séries temporais. Ele combina três componentes: autorregressão (AR), diferenciação (I) e média móvel (MA), sendo eficaz para dados com tendência e sem sazonalidade clara. Ideal para prever valores futuros.

***R***

- [Decomposição](/r_data_science/series_temporais/series.ipynb)  
A decomposição de séries temporais separa os dados em componentes: tendência, sazonalidade e ruído (resíduo). Isso ajuda a entender o comportamento ao longo do tempo, facilitando a análise e a previsão. Pode ser aditiva ou multiplicativa, dependendo da relação entre os componentes.

## 6. Regressão Linear

***Python***

- [Simples](/python_data_science/regressao_linear/regressao_simples.ipynb)  
A regressão linear simples é uma técnica estatística usada para prever o valor de uma variável com base em outra. Ela ajusta uma linha reta aos dados, representando a relação entre uma variável independente (X) e uma dependente (Y). É útil para identificar tendências e fazer previsões.

***R***

- [Múltipla](/r_data_science/regressao_linear/multipla.ipynb)  
A regressão linear múltipla é uma técnica estatística que analisa a relação entre uma variável dependente e duas ou mais variáveis independentes. Ela permite entender como vários fatores influenciam um resultado e é amplamente usada em previsões e análise de dados complexos.


## 7. Regressão Logística

A regressão logística é usada para prever resultados categóricos, como “sim” ou “não”. Em vez de uma linha reta, ela utiliza uma curva em forma de S (sigmoide) para modelar a probabilidade de um evento ocorrer com base em variáveis independentes. É comum em classificações binárias.

- [Python](/python_data_science/regressao_logistica/logistica.ipynb)
- [R](/r_data_science/regressao_logistica/logistica.ipynb)


## 8. Grafos

***Python***

- [Comunidades](/python_data_science/grafos/comunidades.ipynb)  
Em grafos, comunidades são grupos de nós mais conectados entre si do que com o restante da rede. Identificar essas comunidades ajuda a entender a estrutura e relações internas, sendo útil em redes sociais, biológicas e de informação.

***R***

- [Grafos Clássicos](/r_data_science/grafos/grafos_classicos.ipynb)  
Grafos clássicos são modelos com estruturas bem definidas, usados em teoria dos grafos. Exemplos: Grafo completo (todos os vértices conectados), Grafo ciclo (forma um círculo), Grafo caminho (vértices em linha) e Grafo bipartido (vértices divididos em dois grupos, com conexões entre grupos).


## 9. Machine Learning

***Python***

- [Árvore de Decisão](/python_data_science/machine_learning/arvores_de_decisao.ipynb)  
A Árvore de Decisão é um modelo de machine learning usado para classificação e regressão. Ela divide os dados em subgrupos com base em características (atributos), criando uma estrutura de árvore onde cada nó representa uma decisão ou uma divisão, e as folhas indicam os resultados ou previsões.

***R***

- [Naive Bayes](/r_data_science/machine_learning/naive_bayes.ipynb)  
O Naive Bayes é um algoritmo de classificação baseado no teorema de Bayes, assumindo que as características são independentes entre si (daí o "naive", ou ingênuo). Ele calcula a probabilidade de cada classe com base nas características, sendo simples, rápido e eficaz para problemas de classificação.


## 10. Deep Learning

***Python***

- [Redes Neurais](/python_data_science/neural_network_deep_learning/rede_neural.ipynb)  
Deep Learning é uma área da inteligência artificial que usa redes neurais profundas para aprender padrões complexos. As redes neurais simulam o cérebro humano com camadas de neurônios artificiais, sendo eficazes em tarefas como reconhecimento de voz, imagem e linguagem natural. Quanto mais camadas, mais capacidade de aprender representações abstratas dos dados.

***R***

- [Multilayer Perception](/r_data_science/neural_network_deep_learning/multilayer_perceptron.ipynb)  
O Multilayer Perceptron (MLP) é um tipo de rede neural artificial composta por camadas: uma de entrada, uma ou mais ocultas e uma de saída. Cada neurônio em uma camada é conectado a todos os da próxima. É usado em tarefas supervisionadas, como classificação e regressão, aprendendo padrões complexos nos dados.


## 11. Linguagem Natural (Mineiração)

***Python***

- [Transformers (GPT)](/python_data_science/mineiracao_linguagem_natural/transformers_gpt.ipynb)  
Transformers são modelos de aprendizado profundo para processamento de linguagem natural (PLN). O GPT (Generative Pretrained Transformer) é um tipo de modelo Transformer que aprende a partir de grandes quantidades de texto, gerando respostas coerentes e contextuais. Ele usa mecanismos de atenção para capturar dependências entre palavras em frases, tornando-o eficaz em tarefas como tradução, resumo e geração de texto.

***R***

- [Mineiração de Textos](/r_data_science/linguagem_natural_mineiracao/mineiracao_textos.ipynb)  
Mineração de Linguagem Natural (PLN) de textos envolve extrair informações úteis a partir de grandes volumes de dados textuais. Técnicas comuns incluem tokenização, análise de sentimentos, extração de entidades (como nomes e lugares), classificação de texto e resumo automático. O objetivo é transformar dados textuais em insights ou ações práticas.


## 12. Spark Databricks

Spark Databricks é uma plataforma baseada em nuvem que integra o Apache Spark com ferramentas de análise de dados. Facilita o processamento de grandes volumes de dados em tempo real, além de permitir machine learning e análise avançada. É uma solução escalável e colaborativa para dados distribuídos e processamento em larga escala.

- [Exploração de Dados](/spark_databricks/explorar_dados.ipynb)
- [Machine Learning](/spark_databricks/machine_learning.ipynb)