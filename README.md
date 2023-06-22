# Análise de Despesas da Equipe de Marketing - Y.Afisha
Projeto do BootCamp Tripleten para Analistas de Dados


## Sobre o Projeto
O projeto tem como objetivo preparar um relatório para a empresa Y.Afisha para otimizar suas despesas com marketing. O projeto analisará os seguintes conjuntos de dados:

- Logs do servidor
- Arquivo de despejo
- Estatísticas de despesas com marketing

O relatório gerado será usado para auxiliar a empresa a tomar decisões estratégicas em relação às despesas de marketing, otimizando os recursos e maximizando os resultados alcançados.

## Etapas do Projeto

O projeto será dividido nas seguintes etapas:

1. **Preparação dos Dados** - Carga dos dados, verificação e preparação para análise.
2. **Geração de Relatórios e Cálculo de Métricas** - Análises específicas sobre o produto, vendas e marketing serão realizadas.
3. **Elaboração de Conclusões e Recomendações** - Baseado nas análises e métricas, serão fornecidas recomendações e conclusões.

## Formato

A tarefa deve ser concluída em um notebook Jupyter, com código inserido nas células de código e explicações de texto nas células markdown.

## Descrição dos Dados

### Tabela "visits"
Contém logs do servidor com informações sobre os acessos ao site Y.Afisha.

- Uid: identificador único do usuário.
- Device: dispositivo utilizado pelo usuário.
- Start Ts: data e hora de início da sessão.
- End Ts: data e hora de finalização da sessão.
- Source Id: identificador da origem do anúncio pelo qual o usuário chegou ao site.

### Tabela "orders"
Contém dados sobre os pedidos realizados pelos usuários.

- Uid: identificador único do usuário que fez o pedido.
- Buy Ts: data e hora do pedido.
- Revenue: receita gerada pela Y.Afisha com o pedido.

### Tabela "costs"
Contém dados sobre as despesas com marketing.

- source_id: identificador da origem do anúncio.
- dt: data.
- costs: despesas relacionadas a essa origem de anúncio nesse dia.

## Conclusões

Após todas as etapas de análise, iremos gerar conclusões com recomendações de investimentos para os especialistas.

## Como rodar o projeto

1. Clone este repositório
2. Instale as bibliotecas necessárias
3. Execute o notebook Jupyter

### Bibliotecas usadas:

- pandas --> análise de dados
- numpy --> geração de gráficos e auxílio ao pandas
- matplotlib.pyplot --> geração de gráficos

## Importação dos Dados

Após a instalação das bibliotecas, os dados serão abertos em diferentes seções para análise da qualidade das bases e realização das correções necessárias.

## Suporte

Se você encontrar qualquer problema na utilização deste projeto, por favor, abra uma issue ou entre em contato. 

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.
