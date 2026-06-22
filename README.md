# Bootcamp Data Analytics - Módulo 05

Colabs desenvolvidos no módulo 05, do curso Data Analytics da WoMakers Code, onde vimos Numpy, Pandas, Data Wrangling e Sklearn Pipelines.

# Numpy
* Conceito de arrays, matrizes e vetores
* Criação de arrays -> np.array
* Arrays com random e randint
* .shape(linhas, colunas) e .ndim(dimensão [1, 2, 3 ou +])
* .flatten() -> para transformar qualquer matriz ou tensor em um vetor
* .reshape() -> transforma as dimensões da array sem perda/alteração de dados
* Tipos de dados numpy: np.int64, np.int32, np.float64, np.float32 (específicos numpy)
* dype para descobrir os tipos de dados. Uma array numpy possui apenas 1 tipo de dado em cada estrutura. Existindo a sobreposição de dados
* float sobrepõe int e booleanos -> int sobrepõe booleanos -> str sobrepõe booleano, int e float
* np.array(['Olá', 'Kim Namjoon', 'Maria Luiza']).dtype -> pega a maior cadeia de strings
* slices (para fatiar arrays) e index (para pegar valores específicos, linhas e colunas)
* .sort() -> ordenando os dados da array
* axis = 0; axis = 1
* mask e fancy indexing
* substituição de valores e uso do where
* sum() -> para somar os valores da array
* keepdims -> para manter as dimensões após o uso de funções de agregação: np.sum, np.mean, np.max
* cumsum() -> para somas cumulativas
* salvando arquivo .txt e .npy -> np.savetxt('array2d', arr2d, delimiter=',') | arr3_arquivo = np.load('array3d.npy')

# Pandas
* Conceito do pandas
* Conceito de dataframes (index, colunas, linhas)
* Tipos de arquivos que podemos usar para criar dataframes
* Criação de dataframes
* .head(), .info(), .shape, .describe(), .sort_values(asceding=False ou ascending=True)
* Criando subconjuntos de colunas ou linhas
* Criando subconjuntos com condições e operadores lógicos
* Multiplas manipulações
* Estatíticas -> .median(), .mode(), .mean(), .min(), .max(), .var(), .std(), .sum(), .quantile() .agg() e groupby()
* Pivot table
* .drop(), .columns, .index, .set_index(), .iloc[], .loc[], .sort_index(level=[], asceding=False, True)
* Criando gráficos para demonstração de dados -> uso do matplotlib.pyplot
* Verificando dados faltosos -> .isna(), .any()
* Transformando dados para o tipo data to_datetime()
* Contando valores .count()
* Transformando valores NaN com fillna()

# Data Wranglin
* Excluindo colunas
* Renomeando colunas
* Regex para transformação de dados (eliminando caracteres ruidosos do meio do dado)
* str.replace, str.contains, na=False
* Cenários de estudo para estudo do pandas
* get_dummies() para a criação das variáveis dummy ou one-hot encoding

# Sklearn Pipelines
* Usando api do gov com dados de ementas 2025 para estudo de caso das ementas paralamentares de 2025 [Portal da Transparência](https://api.portaldatransparencia.gov.br/swagger-ui/index.html#/Emendas%20parlamentares/emendas)
* Usamos todos os conhecimentos das aulas anteriores e depois realizamos uma automatização
