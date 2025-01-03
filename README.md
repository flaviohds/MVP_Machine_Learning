# MVP_Machine_Learning

Trabalho feito para o curso de "Ciência de Dados e Analytics". Formato de Python Notebook comentado. Notebook principal melhor visualizado no [Google Colab](https://colab.research.google.com/github/flaviohds/MVP_Machine_Learning/blob/main/MVP_machine_learning.ipynb) .

O projeto foi dividido em duas partes no mesmo notebook a pedido dos professores. Estão presentes links para os notebooks das partes individuais no notebook principal mencionado acima.

A primeira parte consiste em uma previsão de série temporal utilizando um conselho de modelos de machine learning clássico. O dataset utilizado resume vendas diárias de uma loja focada em materiais de escritório. Mais informações sobre a fonte de dados, uma análise exploratória e os tratamentos de dados utilizados podem ser encontrados no [projeto anterior](https://github.com/flaviohds/MVP_Vendas_Analise).

A segunda parte consiste no fine-tunning do modelo de processamento de linguagem natural (NLP) pré-treinado [Google BERT](https://huggingface.co/bert-base-cased). A tarefa é treinar o modelo para prever a classificação de avaliações de usuários utilizando uma [base de dados de avaliações de produtos da Amazon](https://huggingface.co/datasets/defunct-datasets/amazon_reviews_multi). Ao final, é verificado como este novo modelo ajustado se sai diante de uma nova tarefa de classificar tweets simulados sobre produtos.

Características do problema e técnicas relevantes utilizadas na parte 1:
- Regressão com Machine Learning
- Previsão de série temporal
- Conselho de modelos (ensemble)
- RandomForest, ElasticNet e KNN
- Auto-correlação (lag) de série histórica
- Normalização e padronização
- Ajuste de hiperparâmetros
- [Facebook Prophet](https://facebook.github.io/prophet/)

Características do problema e técnicas relevantes utilizadas na parte 2:

- Deep Learning
- Processamento de linguagem natural
- [Hugging Face](https://huggingface.co/)
- [Google BERT](https://huggingface.co/bert-base-cased)
- Fine-tunning
- Tratamento de dados em formato de texto
- Regex, lematização, stopwords e remoção de caracteres indesejados
- Tokenizadores

O notebook principal do projeto é o arquivo "MVP_machine_learning.ipynb"
