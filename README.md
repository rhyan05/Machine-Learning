
# Machine Learning

Este repositório contém projetos e estudos relacionados a Machine Learning, desenvolvidos utilizando Jupyter Notebooks.

## Sobre

Neste repositório, você encontrará implementações de algoritmos de aprendizado de máquina e exemplos práticos. Um dos modelos destacados é o modelo `Heart`, que está localizado na seção de tratamento e classificação.

## Estrutura do Repositório

- **Notebooks**: Contêm implementações de modelos e experimentos.
- **Modelos**: Incluem o modelo `Heart` e outros modelos para classificação e tratamento de dados.
- **Datasets**: Conjuntos de dados utilizados para os experimentos.

## Pré-requisitos

Para executar os notebooks, você precisará:

- [Google Colab](https://colab.google)
Obs: Se opitar pelo Colab ignorar o tutiral do pip

<br>ou<br>
- Python 3.7 ou superior
- [Jupyter Notebook](https://jupyter.org/)
- Instalar as dependências necessárias (se aplicável):
  ```bash
  pip install numpy pandas
  ```

## Passo a Passo para Utilizar o Modelo de teste utilizando o arquivo  `HEART`

1. **Importar Bibliotecas para Manipular os Dados**
   No início do notebook, importe as seguintes bibliotecas:
   ```python
   import numpy as np
   import pandas as pd
   ```

2. **Carregar os Dados**
   Certifique-se de ter o arquivo de dados `HEART` armazenado no seu Google Drive. Para carregar o arquivo, siga os passos abaixo:
   - Monte o Google Drive no ambiente de execução:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
   - Localize o arquivo `HEART` no Google Drive:
     - Clique no ícone de pastas no lado esquerdo do Colab.
     - Navegue até `My Drive` e localize o arquivo `HEART`.
     - Clique com o botão direito no arquivo (ou nos três pontinhos) e selecione "Copiar caminho".

   - Carregue os dados no notebook usando o seguinte código:
     ```python
     dados = pd.read_csv('/content/drive/MyDrive/seu_caminho', sep=',', encoding='utf-8')
     ```

3. **Visualizar as 10 Primeiras Linhas**
   Após carregar os dados, visualize as 10 primeiras linhas para inspecionar o conteúdo:
   ```python
   dados.head(10)
   ```

4. **Utilizar o Modelo `Heart`**
   Navegue até a seção de tratamento e classificação dentro do repositório para utilizar o modelo `Heart`. Certifique-se de seguir as instruções no notebook correspondente para treinar e testar o modelo com o conjunto de dados carregado.

## Tecnologias Utilizadas

- **Python** - Linguagem utilizada para implementar os algoritmos.
- **Jupyter Notebook** - Ferramenta interativa para desenvolvimento e análise.
- **Bibliotecas**: 
  - `numpy` - Manipulação de arrays numéricos.
  - `pandas` - Manipulação e análise de dados tabulares.

Feito com ❤️ por [rhyan05](https://github.com/rhyan05).
