# Documentação para parte técnica do case
Utilizei o notebook pois apesar de preferir usar meu editor de texto preferido EMACS, para o case o ideal era uma ferramenta rápida e que me ajudasse a também, visualizar os gráficos.

# Considerações iniciais

A princípio resolvi não subir o arquivo CSV disponibilizado para obter os dados necessários.

Portanto, para rodar o notebook sem erros é necessário ter o arquivo específicado na maquina.

Os códigos estão separados por setor no notebook, agindo tal qual funções comuns em códigos do dia a dia.

Os comentários estão em português e o código em inglês. Pessoalmente não gosto e acho impraticável ter dois idiomas no código, portanto sempre dou preferência a escrever em inglês, mas, dado o contexto do case, preferi manter a base do código em inglês e a documentação/comentários em português.

# Insight Cancelamento por Marketing Source

Os dados desse recurso vêm das linhas onde o status do assinante é CANCELED, e os valores da coluna de marketing_souce.

O objetivo desse recurso é obter os dados de quais canais de marketing tiveram o maior número de cancelamento de assinaturas.

# Insight Moda

Os dados desse recurso vêm das linhas onde o status do assinante pode ser tanto active, paused, canceled. Pegando os valores da coluna de recency.

O objetivo desse recurso é obter a moda, ou seja, os números que mais se repetem na coluna de recency dado o status da assinatura.

# Insight Cancelamento por Estados

Os dados desse recurso vêm das linhas onde o status é CANCELED e resgata os valores da coluna state.

O objetivo desse recurso é descobrir quais estados têm o maior número de assinaturas canceladas.
