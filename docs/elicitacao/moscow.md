# Moscow

## Introdução

A técnica de priorização moscow é uma ferramenta útil para gerenciar as expectativas dos stakeholders e definir as prioridades de um projeto. Ela consiste em classificar os requisitos ou as tarefas em quatro categorias, de acordo com a sua importância: Must have (deve ter), Should have (deveria ter), Could have (poderia ter) e Won’t have (não terá). Essas categorias formam o acrônimo moscow.

## Must have (deve ter)

São os requisitos ou as tarefas que são indispensáveis para o projeto, sem os quais ele não pode ser considerado concluído ou satisfatório. Eles representam as necessidades básicas dos stakeholders e devem ser atendidos em primeiro lugar.

## Should have (deveria ter)

São os requisitos ou as tarefas que são importantes para o projeto, mas que não são críticos para o seu funcionamento ou para a sua aceitação. Eles representam as expectativas dos stakeholders e devem ser atendidos se possível, mas podem ser negociados ou comprometidos se necessário.

## Could have (poderia ter)

São os requisitos ou as tarefas que são desejáveis para o projeto, mas que não têm um impacto significativo no seu resultado ou na sua qualidade. Eles representam as preferências dos stakeholders e devem ser atendidos somente se houver tempo e recursos disponíveis, mas podem ser facilmente descartados ou adiados se não houver.

## Won't have (não terá)

São os requisitos ou as tarefas que estão fora do escopo do projeto, que não agregam valor ou que são inviáveis de serem realizados. Eles representam as ideias dos stakeholders que devem ser explicitamente excluídas ou rejeitadas, para evitar confusão ou desperdício de esforço.

## Aplicação

A técnica do moscow foi utilizada com um usuário real do aplicativo, definindo as prioridades dos requisitos levantados para o projeto. A tabela 2 apresenta os requisitos e suas respectivas categorias de prioridade.

### Entrevista

Uma parente de um dos membros do projeto, Dária, foi entrevistada, conforme cronograma apresentado na tabela 1, sobre a necessidade de priorizar os requisitos levantados. O entrevistador usou a técnica do moscow traduzida para o português, para facilitar o entendimento da entrevistada. A entrevista foi gravada e está disponível no áudio 1.

#### Cronograma

| Local | Dia        | Horário |
| ----- | ---------- | -------- |
| TEAMS | 31/04/2023 | 16:00    |

<div style="text-align: center">
<p> Tabela 1: Cronograma planejado para entrevista com usuário do aplicativo (Fonte: autores, 2023). </p>
</div>

<div style="text-align: center">
<audio controls>
  <source src="../../assets/entrevistaMoscow.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
</div>

<div style="text-align: center">
<p> Audio 1: Gravação da entrevista com a Dária para priorização dos requisitos utilizando a técnica do moscow. (Fonte: Autores, 2023). </p>
</div>

| ID      | requisito                                                                                                                                                                            | priorização |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| FST01   | o aplicativo deve permitir que os usuários se registrem fornecendo informações básicas, como nome, sobrenome, endereço de e-mail e senha.                                       | Must          |
| FST02   | o aplicativo deve permitir que os usuários pesquisem acomodações com base em critérios específicos, como localização, datas de check-in e check-out, tipo de quarto e preço. | Must          |
| FST03   | o aplicativo deve permitir que os usuários reservem acomodações selecionadas, inserindo as informações de pagamento e confirmando a reserva.                                    | Must          |
| FST04   | o aplicativo deve permitir que os usuários cancelem suas reservas de acomodação, desde que sejam feitas dentro dos termos e condições estabelecidos pela empresa.               | Must          |
| FST05   | o aplicativo deve permitir que os usuários pesquisem voos com base em critérios específicos, como origem, destino, datas e número de passageiros.                                | Should        |
| FST06   | o aplicativo deve permitir que os usuários reservem voos selecionados, inserindo as informações de pagamento e confirmando a reserva.                                             | Must          |
| FST08   | o aplicativo deve permitir que os usuários gerenciem suas reservas existentes, incluindo a visualização de detalhes da reserva, alterações de datas e cancelamentos.            | Must          |
| FST10   | o aplicativo deve permitir que os usuários visualizem seu histórico de reservas anteriores, incluindo informações como datas, acomodações e voos reservados.                   | Must          |
| NFST01  | o aplicativo deve ser fácil de usar, com interface intuitiva e navegação clara.                                                                                                   | Must          |
| NFST02  | o aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos.                                                                         | Must          |
| NFST03  | o aplicativo deve estar disponível para uso em todos os momentos, com tempos de inatividade mínimos.                                                                               | Should        |
| NFST04  | o aplicativo deve ser seguro, protegendo as informações dos usuários e garantindo a privacidade.                                                                                  | Must          |
| NFST05  | o aplicativo deve ser confiável, com alta disponibilidade e poucas falhas.                                                                                                          | Must          |
| NFST06  | o aplicativo deve ser compatível com uma ampla variedade de dispositivos, navegadores e sistemas operacionais.                                                                      | Must          |
| NFST07  | o aplicativo deve estar disponível em diferentes idiomas e adaptar-se a diferentes regiões e culturas.                                                                             | Must          |
| FB01    | O sistema deve permitir que o usuário possa cadastrar uma conta                                                                                                                     | Must          |
| FB02    | O sistema deve possuir escolha do método de pagamento                                                                                                                               | Must          |
| FB03    | Possibilitar o cadastro de reserva(s) pelo usuário                                                                                                                                  | Must          |
| FB07    | Permitir que um grupo de pessoas reservem um local                                                                                                                                   | Must          |
| FB09    | Sincronizar as datas das reservas com o calendário do usuário                                                                                                                      | Won't         |
| FB12    | Permitir visualização de imagens do local pelo usuário                                                                                                                            | Must          |
| FB13    | Permitir visualização de imagens do carro pelo usuário                                                                                                                            | Must          |
| FB22    | O sistema deve ser capaz de localizar o usuário se permitido                                                                                                                        | Won't         |
| FB23    | O sistema deve sugerir hospedagens de acordo com a localização do usuário                                                                                                         | Won't         |
| FB24    | O sistema deve oferecer uma aba de perguntas                                                                                                                                         | Should        |
| FB25    | O sistema deve conter um bate-papo para contato com o locatário ou empresa em que foi feito a reserva                                                                               | Should        |
| FB26    | O sistema deve ter um sistema de pontuação ligada ao usuário                                                                                                                      | Should        |
| FB27    | O usuário deve poder denunciar contas                                                                                                                                               | Must          |
| FB31    | Deve existir uma pesquisa por comando de voz                                                                                                                                         | Should        |
| FB04    | Permitir o cancelamento de reserva pelo usuário                                                                                                                                     | Must          |
| FB05    | Permitir que o usuário acesse o histórico de suas reservas                                                                                                                         | Could         |
| FB06    | Permitir a pesquisa de reserva pelo usuário                                                                                                                                         | Must          |
| FB28    | O usuário deve poder avaliar e comentar reservas                                                                                                                                    | Must          |
| FOBS01  | Deve ser possível criar uma conta com o google, facebook ou email pessoal.                                                                                                          | Won´t        |
| FOBS02  | Deve ser possível realizar pesquisas.                                                                                                                                               | Must          |
| FOBS03  | Deve possuir um sistema de fidelidade.                                                                                                                                               | Should        |
| FOBS04  | Deve possuir um sistema de informações e recomendações.                                                                                                                          | Should        |
| FOBS05  | Deve ser possível filtrar as pesquisas.                                                                                                                                             | Must          |
| FOBS06  | Deve ser possível agendar hospedagem.                                                                                                                                               | Must          |
| FOBS07  | Deve ser possível agendar voos.                                                                                                                                                     | Must          |
| FOBS08  | Deve ser possível alugar carros.                                                                                                                                                    | Must          |
| FOBS10  | O aplicativo deve ter mapa interativo.                                                                                                                                               | Must          |
| FOBS12  | O aplicativo deve ter uma aba de favoritos.                                                                                                                                          | Should        |
| FOBS13  | O aplicativo deve possuir um histórico de reservas.                                                                                                                                 | Should        |
| FOBS14  | O aplicativo deve possuir uma central de ajuda ao usuário.                                                                                                                          | Should        |
| FOBS15  | O aplicativo deve possuir uma área administrativa da conta.                                                                                                                         | Must          |
| FOBS20  | O aplicativo deve apresentar as informações legais sobre o uso para o usuário.                                                                                                    | Must          |
| FOBS22  | O aplicativo deve permitir que o usuário saia da conta.                                                                                                                             | Must          |
| NFOBS01 | A inteface deve ser responsiva.                                                                                                                                                      | Must          |
| NFOBS02 | O sistema deve rodar nas principais plataformas mobile Android e iOS.                                                                                                                | Must          |
| NFOBS03 | O sistema deve ser seguro.                                                                                                                                                           | Must          |
| NFOBS04 | Deve possuir acessibilidade.                                                                                                                                                         | Must          |
| NFB01   | O sistema deve ser seguro                                                                                                                                                            | Must          |
| NFB02   | O sistema deve ter um suporte que funciona 24 horas                                                                                                                                  | Must          |
| NFB03   | O sistema deve garantir a privacidade e segurança dos clientes                                                                                                                      | Must          |
| NFB04   | O sistema deve ter acessibilidade para pessoas cegas                                                                                                                                 | Must          |
| NFB05   | O sistema deve ser multiplataforma: Android e iOS                                                                                                                                    | Must          |
| FST07   | o aplicativo deve permitir que os usuários pesquisem e reservem carros de aluguel com base em critérios específicos, como localização, datas e tipo de veículo.                | Should        |
| FST09   | o aplicativo deve permitir que os usuários avaliem acomodações após a conclusão da estadia, fornecendo uma classificação e feedback por escrito.                              | Must          |
| FB08    | Enviar email sobre o status da reserva                                                                                                                                               | Must          |
| FB10    | O sistema deve possuir uma lista de favoritos para aluguel de carro, hospedagem e voos                                                                                               | Should        |
| FB11    | O sistema deve possuir uma lista de desejos para aluguel de carro, hospedagem e voos                                                                                                 | Should        |
| FB14    | O sistema deve possuir um mapa interativo                                                                                                                                            | Should        |
| FB15    | O sistema deve possuir uma carteira digital                                                                                                                                          | Should        |
| FB18    | O sistema deve possuir uma moeda própria                                                                                                                                            | Won´t        |
| FB19    | O usuário deve poder comprar moedas do sistema                                                                                                                                      | Won´t        |
| FB20    | O sistema deve oferecer uma opção de conta premium                                                                                                                                 | Could         |
| FB21    | O usuário deve poder selecionar o idioma do sistema                                                                                                                                 | Must          |
| FB29    | O sistema deve notificar sobre ofertas                                                                                                                                               | Should        |
| FB30    | O sistema deve ter filtragem de pesquisa de hospedagens, alugueis de carros e voos                                                                                                   | Must          |
| FB32    | O usuário deve poder adicionar itens ao aluguel do carro                                                                                                                            | Must          |
| FOBS01  | Deve ser possível criar uma conta com o google, facebook ou email pessoal.                                                                                                          | Must          |
| FOBS09  | Deve ser possível contratar serviços de táxi.                                                                                                                                     | Must          |
| FOBS11  | Deve ser possível agendar visitas à atrações turísticas.                                                                                                                        | Must          |
| FOBS16  | O aplicativo deve possuir sistema de carteira virtual.                                                                                                                               | Won´t        |
| FOBS18  | O aplicativo deve possuir um sistema de ofertas.                                                                                                                                     | Must          |
| FOBS19  | O aplicativo deve possuir um sistema de configurações do aplicativo.                                                                                                               | Won´t        |
| FB16    | O sistema deve exibir dicas sobre os locais e carros                                                                                                                                 | Must          |
| FB17    | O sistema deve mostrar notícias relacionadas ao turismo                                                                                                                             | Must          |
| NFB06   | O sistema deve ter escalabilidade                                                                                                                                                    | Must          |
| NFOBS05 | Deve ser escalável.                                                                                                                                                                 | Must          |

<div style="text-align: center">
<p> Tabela 2: Requisitos levantados e sua importância utilizando a técnica do moscow (Fonte: autores, 2023). </p>
</div>

A seguir, na tabela 3, estão listadas todas as siglas com seus respectivos significados.

| Sigla | Significado                              |
| ----- | ---------------------------------------- |
| FST   | Requisito funcional de Storytelling      |
| NFST  | Requisito NÃO funcional de Storytelling |
| FB    | Requisito Funcional Brainstorm           |
| NFB   | Requisito Não Funcional Brainstorm      |
| FOBS  | Requisito funcional da Observação      |
| NFOBS | Requisito não funcional da Observação |

<div style="text-align: center">
<p> Tabela 3: Tabela de siglas com seus respectivos significados. (Fonte: Autores, 2023). </p>
</div>

## Termo de consentimento

[Termo de consentimento](../assets/pdfs/consentimento_moscow_assinado.pdf)

## Bibliografia

- SILVA, A. L. da. MoSCoW: uma técnica de priorização de requisitos. Disponível em: [https://www.devmedia.com.br/moscow-uma-tecnica-de-priorizacao-de-requisitos/28191](https://www.devmedia.com.br/moscow-uma-tecnica-de-priorizacao-de-requisitos/28191). Acesso em: 25 abr. 2023.
- SANTOS, R. F. dos. Como priorizar requisitos usando a técnica MoSCoW. Disponível em: [https://blog.mastertech.com.br/como-priorizar-requisitos-usando-a-tecnica-moscow/](https://blog.mastertech.com.br/como-priorizar-requisitos-usando-a-tecnica-moscow/). Acesso em: 25 abr. 2023.
- OLIVEIRA, M. A. de. Priorização de requisitos com MoSCoW: o que é e como aplicar? Disponível em: [https://www.euax.com.br/2019/06/priorizacao-de-requisitos-com-moscow/](https://www.euax.com.br/2019/06/priorizacao-de-requisitos-com-moscow/). Acesso em: 25 abr. 2023.
- SOUZA, R. C. de. Técnica MoSCoW para priorização de requisitos de software. Disponível em: [https://www.tiespecialistas.com.br/tecnica-moscow-para-priorizacao-de-requisitos-de-software/](https://www.tiespecialistas.com.br/tecnica-moscow-para-priorizacao-de-requisitos-de-software/). Acesso em: 25 abr. 2023.
- ALVES, T. P. MoSCoW: como priorizar requisitos de forma eficiente? Disponível em: [https://sitecampus.com.br/moscow-como-priorizar-requisitos-de-forma-eficiente/](https://sitecampus.com.br/moscow-como-priorizar-requisitos-de-forma-eficiente/). Acesso em: 25 abr. 2023.
- Moscow do grupo Lichess. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/priorizacao/#moscow](https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/priorizacao/#moscow). Acesso em 25 abr. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                                          | Autor(es)                  | Revisor(es)        |
| ------- | ---------- | ---------------------------------------------------- | -------------------------- | ------------------ |
| 1.0     | 25/04/2023 | Criação da página                                 | Lucas, Henrique e Chaydson | Pedro, Samuel      |
| 1.1     | 30/04/2023 | Adicionando entrevista com o usuário                | Lucas                      | Chaydson, Henrique |
| 1.2     | 30/04/2023 | Atualizando tabela moscow de acordo com a entrevista | Chaydson, Henrique         | Lucas              |
