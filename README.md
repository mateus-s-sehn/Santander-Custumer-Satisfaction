# Santander-Custumer-Satisfaction
Santander Custumer Satisfaction
Definindo o problema de negocio
De equipes de suporte de linha de frente a C-suites, a satisfação do cliente é uma medida chave de sucesso. Os clientes insatisfeitos não ficam por perto. Além do mais, clientes insatisfeitos raramente expressam sua insatisfação antes de sair.

O Banco Santander está pedindo aos Kagglers que os ajudem a identificar clientes insatisfeitos no início de seu relacionamento. Isso permitiria ao Santander tomar medidas proativas para melhorar a felicidade do cliente antes que seja tarde demais.

Nesta competição, você trabalhará com centenas de recursos anônimos para prever se um cliente está satisfeito ou insatisfeito com sua experiência bancária.Você recebe um conjunto de dados anônimo contendo um grande número de variáveis numéricas. A coluna "TARGET" é a variável a ser prevista. É igual a um para clientes insatisfeitos e 0 para clientes satisfeitos.

A tarefa é prever a probabilidade de cada cliente do conjunto de testes ser um cliente insatisfeito.

Você recebe um conjunto de dados anônimo contendo um grande número de variáveis numéricas. A coluna "TARGET" é a variável a ser prevista. É igual a um para clientes insatisfeitos e 0 para clientes satisfeitos.

A tarefa é prever a probabilidade de cada cliente do conjunto de testes ser um cliente insatisfeito.

Descrições de arquivo

train.csv - o conjunto de treinamento incluindo o alvo \ test.csv - o conjunto de teste sem o alvo \ sample_submission.csv - um arquivo de envio de amostra no formato correto

Para cada ID no conjunto de teste, você deve prever uma probabilidade para a variável TARGET. O arquivo deve conter um cabeçalho e ter o seguinte formato:

ID,TARGET \ 2,0 \ 5,0 \ 6,0 \ etc.

As inscrições são avaliadas na área sob a curva ROC entre a probabilidade prevista e o alvo observado.
