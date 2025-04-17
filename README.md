# Previsão da Cotação do Dólar com Redes Neurais LSTM

Este projeto utiliza modelos de redes neurais recorrentes (LSTM) para prever a cotação do dólar em relação ao real nos próximos 3 meses, com base em dados históricos de séries temporais.

## 📌 Objetivo

Criar um modelo de machine learning capaz de antecipar tendências cambiais utilizando técnicas de deep learning aplicadas a séries temporais financeiras.

## 📊 Dados Utilizados

- Fonte: Yahoo Finance (`USD/BRL`)
- Frequência: Diária
- Período: Últimos 5 anos

## ⚙️ Tecnologias

- Python 3.11
- yfinance
- pandas
- numpy
- scikit-learn
- keras / TensorFlow
- matplotlib

## 📈 Modelo

- Tipo: LSTM (Long Short-Term Memory)
- Janela de entrada: 60 dias
- Saída: Previsão dos próximos 3 meses (63 dias úteis)

## 📤 Resultado

O modelo foi capaz de prever a tendência de valorização ou desvalorização do dólar em relação ao real com base no comportamento histórico dos preços. Os dados foram visualizados em gráficos com as previsões em destaque.

## 📁 Como Executar

1. Instale as dependências:
   ```bash
   pip install yfinance pandas numpy scikit-learn matplotlib tensorflow

