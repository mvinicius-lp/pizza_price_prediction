# Previsão de Preço de Pizza

Este projeto utiliza um modelo de regressão linear para prever o preço de uma pizza com base no diâmetro. A interface é construída usando o Streamlit para facilitar a interação do usuário.

## Descrição

O projeto carrega um conjunto de dados de pizzas de um arquivo CSV (`pizzas.csv`), treina um modelo de regressão linear com o diâmetro das pizzas como entrada e o preço como saída, e usa esse modelo para prever o preço de uma pizza com um diâmetro especificado pelo usuário.

## Pré-requisitos

- Python 3.6 ou superior
- Bibliotecas Python: `streamlit`, `pandas`, `scikit-learn`, `matplotlib`, `scikit-learn`

## Instalação

1. Clone este repositório:
   git clone https://github.com/mvinicius-lp/pizza_price_prediction.git
   cd seu_repositorio

2. Instale as dependências:
   pip install -r requirements.txt

3. Certifique-se de que o arquivo `pizzas.csv` esteja presente no diretório principal do projeto.

## Como Executar

1. Inicie o aplicativo Streamlit:
   streamlit run app.py

2. Insira o diâmetro da pizza na interface para obter o preço previsto.

## Estrutura do Código

- `app.py`: O script principal que contém o código para carregar os dados, treinar o modelo e exibir a interface do usuário.

## Uso

Após iniciar o aplicativo, uma página será carregada onde você pode inserir o diâmetro da pizza. O preço previsto será exibido junto com uma animação de balões.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias.
