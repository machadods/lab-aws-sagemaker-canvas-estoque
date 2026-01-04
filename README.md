Previsão de Estoque Inteligente – Notebook

Descrição:
Este notebook tem como objetivo desenvolver um modelo de previsão de estoque utilizando técnicas de Machine Learning. Serão analisados dados de produtos, preços, promoções e histórico de estoque para prever a quantidade necessária em períodos futuros.

Objetivos do projeto:

Explorar e analisar o dataset de estoque, preços e promoções.

Pré-processar os dados e preparar features para o modelo.

Treinar um modelo de regressão usando LightGBM, avaliando sua performance com métricas como RMSE, MAE e R².

Visualizar previsões, resíduos e importância das features.

Gerar insights para decisões de negócio, como reposição de estoque, promoções e planejamento de compras.

Ferramentas e bibliotecas utilizadas:

Python: Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn: pré-processamento e métricas

LightGBM: modelo de regressão baseado em Gradient Boosting

Google Colab: ambiente de execução

Resumo do fluxo do notebook:

Análise exploratória de dados (EDA)

Pré-processamento e encoding de variáveis categóricas

Treinamento e validação do modelo

Avaliação de performance e análise de erros

Visualização de resultados e insights acionáveis

Nota sobre a escolha do ambiente

Este projeto foi desenvolvido no Google Colab devido a uma limitação técnica: o AWS SageMaker Canvas estava me sacaneando e a video aula não apresentava semelhanças com o atual site me fazendo perder horas e não foi possível executar o treinamento diretamente na plataforma.

O Colab foi a alternativa ideal porque:

Execução imediata: Permite rodar todo o fluxo de Machine Learning sem depender de serviços externos.

Controle total do código: Podemos implementar, ajustar e documentar cada etapa do pré-processamento, treinamento e avaliação do modelo.

Integração com Google Drive: Facilita carregar datasets e salvar resultados, mantendo todo o projeto organizado.

Reprodutibilidade e portfólio: Todo o processo fica registrado em células de código e markdown, tornando o notebook didático e pronto para apresentação.

Assim, apesar de originalmente previsto para SageMaker Canvas, o projeto manteve toda a funcionalidade e aprendizado esperado, demonstrando de forma clara o pipeline de previsão de estoque inteligente.
