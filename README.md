# Porsche_Dashboard
endereço da deshboard: https://gustavosm38-rgb.github.io/Porsche_Dashboard/
Painel Executivo de Vendas da Porsche
#Foi feito um Dashboard Financeiro que reponde a evolução das vendas ao longo do tempo, a receita por modelo e a participação por método de pagamento. Foram escolhidas essas perguntas para efetuar uma análise financeira sobre as vendas.
#Foi utilizado o Gemini como ferramenta para a geração do dashboard, gerando o código para inclusão no bloco de notas, sendo salvo como HTML. Criei um agente especializado em criação de dashboards baseado em dados recebidos por planilhas e arquivos em PDF. 
# O prompt utilizado foi:"Olá, Gemini! Crie um dashboard a partir da planilha anexa, com as seguintes regras:
- Três perguntas de negócio escolhidas por mim, cada uma respondida por um gráfico ou indicador;
- Filtros que deixem recortar os dados, como modelo, cidade, ano ou método de pagamento;
- Indicadores de topo, como total de vendas e receita;
- Um visual coerente, com a paleta e a tipografia da empresa automobilística Porsche.
Perguntas de negócio (respondidas com gráficos/indicadores)
Qual é a receita total por modelo de Porsche?
→ Gráfico de barras mostrando a soma de SalesPriceSanitized por PorscheModelSanitized.
Quais são os métodos de pagamento mais utilizados e sua participação na receita?
→ Gráfico de pizza com a distribuição de SalesPriceSanitized por PayMethodSanitized.
Como está a evolução das vendas ao longo do tempo?
→ Gráfico de linha com SalesPriceSanitized por SaleDateSanitized (corrigindo os registros válidos).

Foi utilizada a planilha tratada e somente com as colunas Sanitized.


Ao final, lembre-se de gerar o arquivo html com o dashboard interativo. 

