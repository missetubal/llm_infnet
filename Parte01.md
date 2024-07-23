Conceitos Fundamentais dos LLMs

1. Pre-training
   É considerada a primeira fase do treinamento e consiste em treinar o modelo para que ele aprenda os padrões linguísticos, gramática e relações semânticas.
   Ex.: Modelo sendo treinado com notícias de jornais, onde o modelo aprende a reconhecer padrões de sequências de palavras, estrutura do texto, relações semânticas.

2. Transfer Learning
   A aprendizagem por transferência reutiliza o conhecimento do pré-treinamento e aplica em um conjunto de dados menor que estão mais direcionados a uma tarefa em específico.
   Ex.: O mesmo modelo que foi treinado com notícias gerais, ser usado para tratar apenas de notícias do Mercado Imobiliário.

3. Embedding
   Representação numérica de palavras ou frases, absorvendo o significado semântico entre as palavras.
   Ex.: Palavras como gato e cachorro são representadas por vetores semelhantes porque o modelo reconhece que elas são do mesmo campo semântico.

4. Transformers
   Arquitetura de rede neural feita para lidar com textos sequênciais capturando a relação entre as palavras.
   Ex.: BERT

5. Attention
   Mecanismo que permite que o modelo foque em diferentes partes do input produzindo uma saída, calculando pesos para deerminar a importância das palavras.
   Ex.: "Qual a capital da Bahia?" nesse prompt seria dado um peso maior a "capital" e "Bahia"

6. Fine-Tuning
   A etapa final do treinamento onde os parâmetros são reajustados para que o modelo melhore suas habilidades e tenha um mellhor desempenho.
   O modelo pode identificar tópicos especificos de uma grande lista de noticias.
