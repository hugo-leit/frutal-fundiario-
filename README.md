🌍 Análise Fundiária do Município de Frutal-MG

Este projeto explora a distribuição e concentração de terras rurais no município de Frutal-MG, utilizando dados públicos extraídos de cadastros de imóveis rurais. Através de análises estatísticas, visualizações gráficas e indicadores econômicos, revelamos padrões de posse, prováveis inconsistências cadastrais e o perfil jurídico dos proprietários.

🔢 Objetivos

Identificar os maiores proprietários rurais de Frutal-MG

Medir a desigualdade na distribuição fundiária via índice de Gini

Analisar a participação de diferentes tipos de natureza jurídica (PF, PJ, Associações, Fundações)

Verificar possível sobreposição fundiária ou excesso de área registrada

📊 Principais Resultados

⭐ Índice de Gini Fundiário: 0,6221 → indica alta concentração de terras

⭐ 114,6% da área total do município está registrada em imóveis → indício de sobreposição ou falhas cadastrais

⭐ Pessoas jurídicas como Sociedades Empresárias Ltda e S.A. concentram as maiores propriedades

⭐ Entidades religiosas e fundacionais ocupam parcelas modestas, mas identificáveis

⭐ Mais de 3.500 titulares aparecem apenas uma vez, indicando pulverização parcial

📈 Metodologia

Leitura do CSV com pandas, correção de encoding e padronização de colunas

Conversão de valores com separadores brasileiros (ponto de milhar e vírgula decimal)

Normalização de categorias da coluna "natureza jurídica"

Cálculo do índice de Gini com numpy

Visualização com matplotlib e seaborn: histogramas, boxplots e curva de Lorenz

Identificação dos nomes mais frequentes (e raros) entre os titulares

📊 Tecnologias Utilizadas

Python 3

Pandas

Numpy

Seaborn

Matplotlib

Jupyter Notebook

📅 Fontes de Dados

Cadastro de Imóveis Rurais (Frutal-MG)

Dados públicos de natureza jurídica e percentual de detenção

Área oficial do município: 2.426,965 km² (IBGE)

💼 Estrutura do Projeto

frutal-fundiario/
├── data/
│   └── Imoveis_3127107.csv
├── notebook/
│   └── frutal_fundiario_analise.ipynb
├── output/
│   ├── graficos/
│   └── tabelas/
├── README.md

🚀 Como Executar

Clone este repositório

Instale as dependências com pip install -r requirements.txt

Abra o notebook frutal_fundiario_analise.ipynb na pasta /notebook

Execute as células passo a passo

📚 Licença

Este projeto é de uso educacional e livre, com dados públicos. Sinta-se à vontade para clonar, adaptar e usar os códigos em estudos ou análises similares.

Criado por Vitor Leite como parte de um estudo independente de geoinformação fundiária.
