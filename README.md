[![author](https://img.shields.io/badge/author-JoaoFelizardo-red.svg)](https://www.linkedin.com/in/joaofelizardos/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/)

<p align="center">
  <img src="https://institucional.ifood.com.br/wp-content/uploads/2022/02/vantagens-cultura-data-driven.jpg" alt="imagem maneira relacionada ao projeto"height=400px >
</p>

# Análise de Dados do Airbnb: Austin, Texas 🎸

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** detalhada sobre o mercado de aluguéis de curta temporada na cidade de Austin, Texas. O objetivo principal foi entender as dinâmicas de preço, a composição do inventário imobiliário e a confiabilidade estatística das médias regionais.

## 📊 Principais Insights

A análise foi estruturada para extrair conclusões significativas sobre o comportamento do mercado na região:

* **Perfil do Inventário:** O mercado de Austin é massivamente dominado por **casas ou apartamentos inteiros (83,8%)**. Isso indica que a plataforma é utilizada principalmente para locação de residências completas, em vez de quartos compartilhados. A presença de quartos de hotel é mínima, o que reforça o caráter residencial da oferta na cidade.
* **Disparidade de Preços e Outliers:** A variável `price` revelou uma grande amplitude estatística. Enquanto 75% dos imóveis possuem diárias de até **226 dólares**, identificamos valores extremos de até **50.000 dólares**. Através de uma investigação mais profunda, constatamos que esses valores máximos pertencem a proprietários específicos (como RoomPicks e Aishat) e referem-se a quartos de hotel de luxo, fugindo do padrão do mercado imobiliário comum.
* **Geografia do Valor:** A análise por código postal confirmou que a região mais cara, de forma consistente, é o **Centro (78701)**. Embora outras áreas, como **Steiner Ranch (78732)**, apresentem médias elevadas, o volume reduzido de imóveis (apenas 25) torna essa média mais suscetível a variações e menos representativa. Assim, a liderança do Centro é estatisticamente mais sólida, dado o alto volume de ofertas que sustentam seu preço médio elevado.
* **Engajamento dos Usuários:** Notamos que a maioria dos imóveis recebe até 62 avaliações. No entanto, há propriedades extremamente populares com mais de **1.300 reviews**, o que pode ser um indicador de hospitalidade excepcional ou localizações privilegiadas que geram alta rotatividade.

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.12.12
* **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn
* **Ambiente:** Jupyter Notebook

## 📈 O que você encontrará neste projeto

1.  **Obtenção dos Dados:** Extração a partir do portal Inside Airbnb.
2.  **Limpeza e Tratamento:** Identificação de valores ausentes e remoção de variáveis irrelevantes.
3.  **Análise Estatística:** Exploração de variáveis numéricas e categóricas para entender a distribuição dos dados.
4.  **Visualizações:** Gráficos de densidade, histogramas e visualizações geográficas.
5.  **Conclusão:** Síntese dos achados com base em rigor estatístico.

[Link para o projeto completo](https://github.com/joaofelizardooo/analisando_dados_airbnb_austin_texas/blob/main/Analisando_os_Dados_do_Airbnb_(Austin).ipynb)

**Contatos:**
* [LinkedIn](https://www.linkedin.com/in/joaofelizardos/)

