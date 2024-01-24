# Análise de Sentimentos - Projeto de Data Science

Bem-vindo ao meu projeto de Análise de Sentimentos usando técnicas de Data Science! 🚀

## Visão Geral

Este projeto tem como objetivo analisar sentimentos em avaliações de filmes, classificando-as como positivas ou negativas. Utilizei diversas ferramentas e técnicas de Data Science, desde a importação de bibliotecas até a implementação de modelos de Machine Learning.

## Tecnologias Utilizadas

- **Linguagem de Programação:** Python
- **Bibliotecas:** Pandas, NumPy, Matplotlib, NLTK, Scikit-learn
- **Machine Learning:** CatBoost, Naive Bayes (GaussianNB, MultinomialNB, BernoulliNB), Random Forest, Decision Tree
- **Ferramentas:** Jupyter Notebook, Pickle

## Passos do Projeto

1. **Importação e Pré-processamento dos Dados:**
   - Importação da base de dados do IMDB.
   - Análise exploratória de dados para entender a distribuição dos sentimentos (positivo e negativo).
   - Limpeza de dados, removendo tags HTML e caracteres especiais.

2. **Processamento de Texto:**
   - Utilização da biblioteca NLTK para remover stopwords e aplicar stemming.
   - Transformação do texto em vetores para a criação das variáveis de treino e teste.

3. **Treinamento de Modelos:**
   - Configuração e treinamento de diferentes modelos de Machine Learning, incluindo Naive Bayes e Decision Tree.
   - Avaliação da acurácia dos modelos utilizando matrizes de confusão.

4. **Escolha do Modelo Final:**
   - Identificação do modelo BernoulliNB como o mais eficaz na previsão de sentimentos.

5. **Exportação do Modelo Treinado:**
   - Exportação do modelo BernoulliNB em um arquivo .pkl para uso futuro.
   - Criação de um dicionário de termos para a representação do Bag of Words (BoW).

6. **Teste do Modelo:**
   - Teste do modelo com um novo comentário para análise de sentimento em tempo real.

## Aplicações Práticas

- **Sistemas de Recomendação:** A análise de sentimentos pode ser aplicada em sistemas de recomendação de filmes, personalizando as sugestões com base nas preferências do usuário.
- **Feedbacks Automáticos:** Empresas podem utilizar essa abordagem para analisar automaticamente os feedbacks dos clientes, identificando áreas de melhoria.
- **Plataformas Online:** Implementação em redes sociais para análise de sentimentos em comentários e avaliações.

## Como Utilizar o Código

1. Clone o repositório: `git clone [link_do_seu_repositorio]`
2. Execute o Jupyter Notebook: `jupyter notebook SentimentAnalysis.ipynb`
3. Explore o código e as análises feitas em cada etapa.

## Arquivos do Projeto

- `SentimentAnalysis.ipynb`: Jupyter Notebook com o código completo.
- `model1.pkl`: Modelo treinado (BernoulliNB) exportado em formato .pkl.
- `bow.pkl`: Dicionário de termos para a representação do Bag of Words.

Fique à vontade para explorar, fornecer feedback e contribuir para a evolução deste projeto! 🌟


Agradeço por explorar este projeto de Análise de Sentimentos! 🙌🎉